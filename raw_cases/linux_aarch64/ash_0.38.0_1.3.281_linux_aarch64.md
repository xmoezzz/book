# `ash` `0.38.0+1.3.281`

Platform: Linux aarch64

This file contains the unabridged evidence for the corresponding manual-coding case.

## Root-owned build-level evidence

### Network / source acquisition records

_None._

### pkg-config / pkgconf records

_None._

### Build-script executable native dependencies

These records belong to linker steps that construct the Rust build-script executable. They are retained as coding evidence but are separate from produced native-artifact flows.

### Build-script link records

#### Record 1

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib"
  ],
  "libs": [
    "gcc_s",
    "util",
    "rt",
    "pthread",
    "m",
    "dl",
    "c"
  ],
  "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
    "source": "cargo_manifest_dir"
  }
}
```

### Build-script resolved-link records

#### Record 1

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U",
    "/target/debug/build/ash-18b97227eb4289a8",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "/lib/x86_64-linux-gnu"
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib(std-d1237ef7159db0a2.std.e28293b1aa0f68bd-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib(panic_unwind-4be5972b22d3a6da.panic_unwind.d9b2f7d287d2f9d2-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib(object-2a81194c9d07bbf6.object.4f4cc23e276cbdd5-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib(memchr-ea71fa85f6699d6b.memchr.9642f0ce76a98c65-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib(addr2line-a79a8816d9fd6004.addr2line.39b02397e671b2d1-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib(gimli-46dc78dc6a8cb06a.gimli.9d272e8433f81454-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib(rustc_demangle-146c3f1190dee2e2.rustc_demangle.c5a78273c295e539-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib(miniz_oxide-5ad929a15a8e6727.miniz_oxide.b662226d77c6ee8e-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib(adler2-1f570ee5c6635aae.adler2.1d6706876a417dbf-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib(alloc-6e6df4ffe0af4d15.alloc.fdfd2bd8633a6659-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib(core-120cbae4e86ec454.core.c1f1a4ba060b9bfa-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.132.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.187.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.201.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.261.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libutil.so",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/libm.so.6",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/libmvec.so.1",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/libc.so.6",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o",
      "source": "link_trace"
    }
  ],
  "kind": "resolved_link",
  "map_path": "/tmp/native-trace-link-cc-380753-1783994292536935262.map",
  "pid": 380753,
  "ppid": 380724,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-380753-1783994292536935262.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Complete analysis record stream

These are the recovered/enriched/generated records actually supplied to native-flow reconstruction.

### Analysis records

#### Record 1

```json
{
  "event": "native_trace_root_context",
  "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "workspace_root": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281"
  ],
  "packages": [
    {
      "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
      "name": "ash",
      "version": "0.38.0+1.3.281",
      "manifest_path": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.4",
      "name": "cfg-if",
      "version": "1.0.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libloading@0.8.9",
      "name": "libloading",
      "version": "0.8.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.8.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.8.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.1",
      "name": "windows-link",
      "version": "0.2.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1"
    }
  ],
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
    "source": "cwd_prefix"
  }
}
```

#### Record 2

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "exit_code": 0,
  "kind": "exec",
  "pid": 380753,
  "ppid": 380724,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ash",
  "cargo_pkg_version": "0.38.0+1.3.281",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "event_id": "used:cc:1b64b12f73b3f5f8:280f58072b1f5b59:b60e9cb133a16581",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
  "path": "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
  "pid": 380753,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ash",
  "cargo_pkg_version": "0.38.0+1.3.281",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "event_id": "used:cc:1b64b12f73b3f5f8:41bf94100a97eecc:b60e9cb133a16581",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
  "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
  "pid": 380753,
  "sha256": "6c2bcbd54d14990fb951815af4394fe733a8991d87c056c3074d4c84592bdda7",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ash",
  "cargo_pkg_version": "0.38.0+1.3.281",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "event_id": "used:cc:1b64b12f73b3f5f8:933c9b7c2d0b612c:b60e9cb133a16581",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
  "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
  "pid": 380753,
  "sha256": "fd9ed336469fb7d32e271a6b370e5ec230133d1fc37cd504e92c1990e0d9e589",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 6

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ash",
  "cargo_pkg_version": "0.38.0+1.3.281",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "event_id": "used:cc:1b64b12f73b3f5f8:9cc47b6b91eb79b9:b60e9cb133a16581",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
  "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
  "pid": 380753,
  "sha256": "61551e209e4f257575c28b00796ff85b1d51c489d1bf44dfa92f367636558e5e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 7

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ash",
  "cargo_pkg_version": "0.38.0+1.3.281",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "event_id": "used:cc:1b64b12f73b3f5f8:d6fbd98f5bfa8691:b60e9cb133a16581",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
  "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
  "pid": 380753,
  "sha256": "4fb8f4a38765274b150661c5aeecc73054ff8db5349f94525bb99701fcdec28b",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 8

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ash",
  "cargo_pkg_version": "0.38.0+1.3.281",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "event_id": "used:cc:1b64b12f73b3f5f8:119ec797b5cb0944:b60e9cb133a16581",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
  "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
  "pid": 380753,
  "sha256": "8b1dc39858fff23fc1ff13d93442797e2f30c8062659339cf9dbeb32c8be6b38",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 9

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ash",
  "cargo_pkg_version": "0.38.0+1.3.281",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "event_id": "used:cc:1b64b12f73b3f5f8:b4a92224bdd7efdf:b60e9cb133a16581",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
  "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
  "pid": 380753,
  "sha256": "286f1094277661a0dec8686a6ad6da3271263c9fb5556b73cf3ed1a107729102",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 10

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib"
  ],
  "libs": [
    "gcc_s",
    "util",
    "rt",
    "pthread",
    "m",
    "dl",
    "c"
  ],
  "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 11

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "cargo_pkg_name": "ash",
  "cargo_pkg_version": "0.38.0+1.3.281",
  "context_path": "/tmp/native-trace-380033-1783994290236/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-380033-1783994290236/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 380753,
  "ppid": 380724,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 12

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U",
    "/target/debug/build/ash-18b97227eb4289a8",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "/lib/x86_64-linux-gnu"
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib(std-d1237ef7159db0a2.std.e28293b1aa0f68bd-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib(panic_unwind-4be5972b22d3a6da.panic_unwind.d9b2f7d287d2f9d2-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib(object-2a81194c9d07bbf6.object.4f4cc23e276cbdd5-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib(memchr-ea71fa85f6699d6b.memchr.9642f0ce76a98c65-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib(addr2line-a79a8816d9fd6004.addr2line.39b02397e671b2d1-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib(gimli-46dc78dc6a8cb06a.gimli.9d272e8433f81454-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib(rustc_demangle-146c3f1190dee2e2.rustc_demangle.c5a78273c295e539-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib(miniz_oxide-5ad929a15a8e6727.miniz_oxide.b662226d77c6ee8e-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib(adler2-1f570ee5c6635aae.adler2.1d6706876a417dbf-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib(alloc-6e6df4ffe0af4d15.alloc.fdfd2bd8633a6659-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib(core-120cbae4e86ec454.core.c1f1a4ba060b9bfa-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.132.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.187.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.201.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.261.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libutil.so",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/libm.so.6",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/libmvec.so.1",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/libc.so.6",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o",
      "source": "link_trace"
    }
  ],
  "kind": "resolved_link",
  "map_path": "/tmp/native-trace-link-cc-380753-1783994292536935262.map",
  "pid": 380753,
  "ppid": 380724,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-380753-1783994292536935262.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 13

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 0,
  "parsed_event_count": 0,
  "phase": "start",
  "platform": "linux_ebpf",
  "raw_event_count": 0,
  "spawn_error": null,
  "stderr": "",
  "stdout": ""
}
```

#### Record 14

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 1,
  "parsed_event_count": 4000,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 4001,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "fault\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n31.954  build-script-bu  393094 391145   0 /target/debug/build/rustix-0a16b3d645d9d205/build-script-build\n31.958  cc1              393080 393003   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n31.959  aarch64-linux-g  393090 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n31.969  as               393100 392225   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n31.978  cc1              393101 393090   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n31.980  powerpc64le-lin  393091 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n31.983  as               393105 392947   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n31.985  rustc            393102 393094   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --target powerpc64le-unknown-linux-gnu --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/rustix-2befdd4c145c4aba/out -\n32.003  cc1              393106 393091   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.004  as               393099 392639   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.006  riscv64-linux-g  393089 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.008  as               393112 392856   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.008  powerpc64le-lin  393107 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.023  as               393110 392811   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.024  cc1              393122 393107   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.028  cc1              393120 393089   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.029  aarch64-linux-g  393124 391596   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I ...\n32.031  riscv64-linux-g  393119 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.036  cc1              393127 393124   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.040  rustc            393111 391145   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\" -C metadata=9cf788c8acaa5824 ...\n32.047  riscv64-linux-g  393128 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.054  cc1              393129 393119   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.058  powerpc64le-lin  393131 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.059  aarch64-linux-g  393126 391596   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I ...\n32.068  cc1              393151 393128   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.070  cc1              393149 393131   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.082  as               393154 393009   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.083  cc1              393155 393126   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.087  riscv64-linux-g  393130 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.100  as               393163 393007   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.109  aarch64-linux-g  393157 391596   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I ...\n32.112  rustc            393162 391145   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name log --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"kv_unstable\", \"kv_unstable_serde\", \"kv_unstable_std\", \"kv_unstable_sval\", \"max_level_debug\", \"max_level_err -C metadata=2e4c0c2074165706 ...\n32.121  rustc            393156 391145   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name once_cell --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.18.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"race\" ...\n32.121  as               393167 392970   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.125  cc1              393172 393130   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.125  cc1              393170 393157   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.129  riscv64-linux-g  393165 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.141  build-script-bu  393179 391442   0 /target/debug/build/thiserror-35d5289b9aaf462a/build-script-build\n32.145  as               393182 392946   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.149  cc               393175 392833   0 /tmp/native-trace-389767-1783994316079/shims/cc -m64 /target/debug/build/pprof-003116af80e26532/rustcGM7Aer/symbols.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.1ommwjucy2p2mxqxvsktyrpze.0jdd3qc.rcgu.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.29slsntdpaa1mktrjctdmljuw.0jdd3qc.rcgu.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.4vfyzww6v0hzwd14b5gr4eabh.0jdd3qc.rcgu.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.acvu3wu45refsrqvepeowcxo9.0jdd3qc.rcgu.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.bq5mix0lyggzrmcn3ggar52nx.0jdd3qc.rcgu.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.0p081agfvz5y9w1262jx27ymq.0jdd3qc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n32.150  cc1              393181 393165   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.154  rustc            393173 391442   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bitflags --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"default\", \"example_generated\", \"rustc-dep-of-std\")) ...\n32.158  aarch64-linux-g  393168 391596   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I ...\n32.158  riscv64-linux-g  393180 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.162  as               393186 391983   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x509_def.o /tmp/ccWAD3R7.s\n32.168  cc               393185 393175   0 /usr/bin/cc -m64 /target/debug/build/pprof-003116af80e26532/rustcGM7Aer/symbols.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.1ommwjucy2p2mxqxvsktyrpze.0jdd3qc.rcgu.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.29slsntdpaa1mktrjctdmljuw.0jdd3qc.rcgu.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.4vfyzww6v0hzwd14b5gr4eabh.0jdd3qc.rcgu.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.acvu3wu45refsrqvepeowcxo9.0jdd3qc.rcgu.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.bq5mix0lyggzrmcn3ggar52nx.0jdd3qc.rcgu.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.0p081agfvz5y9w1262jx27ymq.0jdd3qc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n32.171  cc1              393192 393168   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.175  rustc            393187 393179   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2018 --crate-name=thiserror_build --crate-type=lib --emit=metadata --out-dir /target/riscv64gc-unknown-linux-gnu/debug/build/thiserror-01a6b7c7d901c723/out /target/riscv64gc-unknown-linux-gnu/debug/build/thiserror-01a6b7c7d901c723/out/probe.rs --target riscv64gc-unknown-linux-gnu\n32.180  riscv64-linux-g  393189 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.180  aarch64-linux-g  393188 391596   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I ...\n32.184  as               393190 392922   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.187  powerpc64le-lin  393191 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.188  as               393195 392924   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.193  as               393201 393083   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.193  cc1              393194 393180   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.195  aarch64-linux-g  393196 391596   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I ...\n32.197  collect2         393202 393185   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccN5tdEu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n32.197  riscv64-linux-g  393198 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.203  cc1              393199 393188   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.207  cc1              393207 393191   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.208  cc1              393197 393189   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.213  aarch64-linux-g  393204 391596   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I ...\n32.220  ld.lld           393214 393202   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccN5tdEu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532 ...\n32.223  rust-lld         393214 393202   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccN5tdEu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n32.225  cc1              393208 393196   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.225  aarch64-linux-g  393210 391596   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I ...\n32.225  cc1              393205 393198   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.227  powerpc64le-lin  393203 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.238  cc1              393221 393203   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.239  as               393218 392906   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.240  cc1              393217 393210   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.242  cc               393206 391525   0 /tmp/native-trace-389767-1783994316079/shims/cc -m64 /target/debug/build/libc-718da79730189469/rustcrNL14W/symbols.o /target/debug/build/libc-718da79730189469/build_script_build-718da79730189469.build_script_build.3d64921cd6e2fc3f-cgu.0.rcgu.o /target/debug/build/libc-718da79730189469/build_script_build-718da79730189469.build_script_build.3d64921cd6e2fc3f-cgu.1.rcgu.o /target/debug/build/libc-718da79730189469/build_script_build-718da79730189469.ckhy8b61128catfiydh0j3gqp.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n32.243  cc1              393215 393204   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.243  as               393220 393052   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.250  as               393222 392931   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.251  powerpc64le-lin  393216 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.257  as               393224 392867   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.266  riscv64-linux-g  393211 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.269  rustc            393209 390978   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lock_api-0.4.10/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"atomic_usize\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n32.275  as               393231 392993   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.277  cc1              393234 393211   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.278  as               393227 392821   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.286  as               393232 392968   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.299  as               393237 393089   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.299  as               393235 392910   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.299  as               393238 392920   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.300  cc               393230 393206   0 /usr/bin/cc -m64 /target/debug/build/libc-718da79730189469/rustcrNL14W/symbols.o /target/debug/build/libc-718da79730189469/build_script_build-718da79730189469.build_script_build.3d64921cd6e2fc3f-cgu.0.rcgu.o /target/debug/build/libc-718da79730189469/build_script_build-718da79730189469.build_script_build.3d64921cd6e2fc3f-cgu.1.rcgu.o /target/debug/build/libc-718da79730189469/build_script_build-718da79730189469.ckhy8b61128catfiydh0j3gqp.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n32.301  as               393236 393003   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.305  cc1              393228 393216   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.310  powerpc64le-lin  393244 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.311  riscv64-linux-g  393229 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.314  as               393243 392997   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.319  rustc            393226 391145   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name object --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/object-0.31.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"archive\" --cfg feature=\"coff\" --cfg feature=\"elf\" ...\n32.321  cc1              393256 393244   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.327  as               393266 392999   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.327  as               393246 393041   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.330  cc1              393248 393229   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.339  collect2         393276 393230   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDN9JsG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n32.341  powerpc64le-lin  393253 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.359  aarch64-linux-g  393277 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n32.360  as               393289 393031   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.360  as               393290 393107   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.360  cc1              393284 393253   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.363  rustc            393281 390978   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name object --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/object-0.31.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"archive\" --cfg feature=\"coff\" --cfg feature=\"elf\" ...\n32.370  ld.lld           393292 393276   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDN9JsG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-718da79730189469/build_script_build-718da79730189469 ...\n32.378  cc1              393291 393277   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n32.379  powerpc64le-lin  393282 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.387  build-script-bu  393298 390978   0 /target/debug/build/rustix-0a16b3d645d9d205/build-script-build\n32.387  rust-lld         393292 393276   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDN9JsG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n32.390  powerpc64le-lin  393296 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.397  build-script-bu  393288 390978   0 /target/debug/build/cpp_demangle-74990a41cb4e36c9/build-script-build\n32.404  powerpc64le-lin  393300 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.404  cc1              393301 393282   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.411  rustc            393299 393298   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --target aarch64-unknown-linux-gnu --out-dir /target/aarch64-unknown-linux-gnu/debug/build/rustix-f23dfed64fb951b9/out -\n32.412  cc1              393305 393300   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.427  cc1              393306 393296   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.429  as               393311 393211   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.437  riscv64-linux-g  393310 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.439  powerpc64le-lin  393309 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.442  cc1              393317 393310   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.446  as               393313 392954   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.446  riscv64-linux-g  393318 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.456  as               393320 393126   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.456  cc1              393327 393309   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.458  as               393322 393091   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.460  cc1              393330 393318   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.463  powerpc64le-lin  393321 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.463  as               393329 393203   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.474  as               393334 393165   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.484  riscv64-linux-g  393328 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.491  as               393339 392729   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x509_txt.o /tmp/ccPJJcex.s\n32.495  cc1              393337 393321   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.498  as               393343 393168   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.500  cc               393335 391205   0 /tmp/native-trace-389692-1783994315897/shims/cc -m64 /target/debug/build/cpp_demangle-74990a41cb4e36c9/rustcPI0P9H/symbols.o /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.build_script_build.c55557ca43dcbfdc-cgu.0. /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.build_script_build.c55557ca43dcbfdc-cgu.1. /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.build_script_build.c55557ca43dcbfdc-cgu.2. /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.build_script_build.c55557ca43dcbfdc-cgu.3. /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.build_script_build.c55557ca43dcbfdc-cgu.4. /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.21jqvq05iyeumrh72nepedxol.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n32.500  as               393344 393180   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.504  powerpc64le-lin  393333 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.504  riscv64-linux-g  393338 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.505  as               393340 393024   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.508  cc1              393341 393328   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.518  cc1              393351 393338   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.527  cc               393350 393335   0 /usr/bin/cc -m64 /target/debug/build/cpp_demangle-74990a41cb4e36c9/rustcPI0P9H/symbols.o /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.build_script_build.c55557ca43dcbfdc-cgu.0. /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.build_script_build.c55557ca43dcbfdc-cgu.1. /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.build_script_build.c55557ca43dcbfdc-cgu.2. /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.build_script_build.c55557ca43dcbfdc-cgu.3. /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.build_script_build.c55557ca43dcbfdc-cgu.4. /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.21jqvq05iyeumrh72nepedxol.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n32.534  as               393370 392929   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.539  powerpc64le-lin  393346 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.541  riscv64-linux-g  393349 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.544  as               393372 392422   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x509_req.o /tmp/ccV1HQgh.s\n32.549  collect2         393373 393350   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnGnk3t.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n32.556  cc1              393377 393346   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.559  cc1              393347 393333   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.561  cc1              393380 393349   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.561  as               393345 393131   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.568  as               393383 392728   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.571  ld.lld           393381 393373   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnGnk3t.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9 ...\n32.575  as               393384 393198   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.576  as               393386 393119   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.579  rustc            393312 390978   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cpp_demangle --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n32.585  powerpc64le-lin  393379 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.586  aarch64-linux-g  393387 391596   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I ...\n"
}
```

#### Record 15

```json
{
  "argv": [
    "/target/debug/build/ash-18b97227eb4289a8/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 380793,
  "build_script_target_dir": "ash-18b97227eb4289a8",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/ash-18b97227eb4289a8/build-script-build",
  "pid": 380793,
  "ppid": 380715,
  "root_cargo_pid": 380715,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "_build_script_out_dir": "/target/debug/build/ash-18b97227eb4289a8/out"
}
```

#### Record 16

```json
{
  "crate": "ash",
  "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "event_id": "bsrun:89be77ac998fe6f8:f1d2e4686d87d918:2a08caf2034bc188",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/ash-18b97227eb4289a8/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
  "out_dir": "/target/debug/build/ash-18b97227eb4289a8/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
  "success": true,
  "target": null,
  "version": "0.38.0+1.3.281",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
    "source": "cwd_prefix"
  }
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T01:58:45.805878+00:00",
  "crate": "ash",
  "version": "0.38.0+1.3.281",
  "architecture": "aarch64",
  "duration_seconds": 39.54073624685407,
  "trace_record_count": 16,
  "trace_owner_summary": {
    "owner_package_count": 4,
    "owner_packages": [
      {
        "crate": "windows-link",
        "version": "0.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1/Cargo.toml"
      },
      {
        "crate": "libloading",
        "version": "0.8.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libloading@0.8.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.8.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.8.9/Cargo.toml"
      },
      {
        "crate": "cfg-if",
        "version": "1.0.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/Cargo.toml"
      },
      {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
        "manifest_path": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281/Cargo.toml"
      }
    ],
    "attributed_event_count": 13,
    "unattributed_event_count": 3,
    "owners": [
      {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "event_count": 13,
        "kind_counts": {
          "native_trace_root_context": 1,
          "exec": 1,
          "used_input": 7,
          "link": 1,
          "exec_context": 1,
          "resolved_link": 1,
          "build_script_run": 1
        }
      }
    ]
  },
  "trace_records": [
    {
      "event": "native_trace_root_context",
      "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
      "workspace_root": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281"
      ],
      "packages": [
        {
          "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
          "name": "ash",
          "version": "0.38.0+1.3.281",
          "manifest_path": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.4",
          "name": "cfg-if",
          "version": "1.0.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libloading@0.8.9",
          "name": "libloading",
          "version": "0.8.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.8.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.8.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.1",
          "name": "windows-link",
          "version": "0.2.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1"
        }
      ],
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
      "exit_code": 0,
      "kind": "exec",
      "pid": 380753,
      "ppid": 380724,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ash",
      "cargo_pkg_version": "0.38.0+1.3.281",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
      "event_id": "used:cc:1b64b12f73b3f5f8:280f58072b1f5b59:b60e9cb133a16581",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
      "path": "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
      "pid": 380753,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ash",
      "cargo_pkg_version": "0.38.0+1.3.281",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
      "event_id": "used:cc:1b64b12f73b3f5f8:41bf94100a97eecc:b60e9cb133a16581",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
      "pid": 380753,
      "sha256": "6c2bcbd54d14990fb951815af4394fe733a8991d87c056c3074d4c84592bdda7",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ash",
      "cargo_pkg_version": "0.38.0+1.3.281",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
      "event_id": "used:cc:1b64b12f73b3f5f8:933c9b7c2d0b612c:b60e9cb133a16581",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
      "pid": 380753,
      "sha256": "fd9ed336469fb7d32e271a6b370e5ec230133d1fc37cd504e92c1990e0d9e589",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ash",
      "cargo_pkg_version": "0.38.0+1.3.281",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
      "event_id": "used:cc:1b64b12f73b3f5f8:9cc47b6b91eb79b9:b60e9cb133a16581",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
      "pid": 380753,
      "sha256": "61551e209e4f257575c28b00796ff85b1d51c489d1bf44dfa92f367636558e5e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ash",
      "cargo_pkg_version": "0.38.0+1.3.281",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
      "event_id": "used:cc:1b64b12f73b3f5f8:d6fbd98f5bfa8691:b60e9cb133a16581",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
      "pid": 380753,
      "sha256": "4fb8f4a38765274b150661c5aeecc73054ff8db5349f94525bb99701fcdec28b",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ash",
      "cargo_pkg_version": "0.38.0+1.3.281",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
      "event_id": "used:cc:1b64b12f73b3f5f8:119ec797b5cb0944:b60e9cb133a16581",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
      "pid": 380753,
      "sha256": "8b1dc39858fff23fc1ff13d93442797e2f30c8062659339cf9dbeb32c8be6b38",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ash",
      "cargo_pkg_version": "0.38.0+1.3.281",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
      "event_id": "used:cc:1b64b12f73b3f5f8:b4a92224bdd7efdf:b60e9cb133a16581",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
      "pid": 380753,
      "sha256": "286f1094277661a0dec8686a6ad6da3271263c9fb5556b73cf3ed1a107729102",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib"
      ],
      "libs": [
        "gcc_s",
        "util",
        "rt",
        "pthread",
        "m",
        "dl",
        "c"
      ],
      "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
      "cargo_pkg_name": "ash",
      "cargo_pkg_version": "0.38.0+1.3.281",
      "context_path": "/tmp/native-trace-380033-1783994290236/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-380033-1783994290236/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 380753,
      "ppid": 380724,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U",
        "/target/debug/build/ash-18b97227eb4289a8",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "/lib/x86_64-linux-gnu"
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U",
          "kind": "object",
          "path": "/target/debug/build/ash-18b97227eb4289a8/rustcX0X25U/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ash-18b97227eb4289a8",
          "kind": "object",
          "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.1hjzdec.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ash-18b97227eb4289a8",
          "kind": "object",
          "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.1hjzdec.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ash-18b97227eb4289a8",
          "kind": "object",
          "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.1hjzdec.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ash-18b97227eb4289a8",
          "kind": "object",
          "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.1hjzdec.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ash-18b97227eb4289a8",
          "kind": "object",
          "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.1hjzdec.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ash-18b97227eb4289a8",
          "kind": "object",
          "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.1hjzdec.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib(std-d1237ef7159db0a2.std.e28293b1aa0f68bd-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib(panic_unwind-4be5972b22d3a6da.panic_unwind.d9b2f7d287d2f9d2-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib(object-2a81194c9d07bbf6.object.4f4cc23e276cbdd5-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib(memchr-ea71fa85f6699d6b.memchr.9642f0ce76a98c65-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib(addr2line-a79a8816d9fd6004.addr2line.39b02397e671b2d1-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib(gimli-46dc78dc6a8cb06a.gimli.9d272e8433f81454-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib(rustc_demangle-146c3f1190dee2e2.rustc_demangle.c5a78273c295e539-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib(miniz_oxide-5ad929a15a8e6727.miniz_oxide.b662226d77c6ee8e-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib(adler2-1f570ee5c6635aae.adler2.1d6706876a417dbf-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib(alloc-6e6df4ffe0af4d15.alloc.fdfd2bd8633a6659-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib(core-120cbae4e86ec454.core.c1f1a4ba060b9bfa-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.132.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.187.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.201.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.261.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libutil.so",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so",
          "source": "link_trace"
        },
        {
          "directory": "/lib/x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/lib/x86_64-linux-gnu/libm.so.6",
          "source": "link_trace"
        },
        {
          "directory": "/lib/x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/lib/x86_64-linux-gnu/libmvec.so.1",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so",
          "source": "link_trace"
        },
        {
          "directory": "/lib/x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/lib/x86_64-linux-gnu/libc.so.6",
          "source": "link_trace"
        },
        {
          "directory": "/lib/x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o",
          "source": "link_trace"
        }
      ],
      "kind": "resolved_link",
      "map_path": "/tmp/native-trace-link-cc-380753-1783994292536935262.map",
      "pid": 380753,
      "ppid": 380724,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-380753-1783994292536935262.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "/usr/local/bin/execsnoop",
        "-t"
      ],
      "event": "process_tracer_diagnostic",
      "exit_status": null,
      "parse_error_count": 0,
      "parsed_event_count": 0,
      "phase": "start",
      "platform": "linux_ebpf",
      "raw_event_count": 0,
      "spawn_error": null,
      "stderr": "",
      "stdout": ""
    },
    {
      "argv": [
        "/usr/local/bin/execsnoop",
        "-t"
      ],
      "event": "process_tracer_diagnostic",
      "exit_status": null,
      "parse_error_count": 1,
      "parsed_event_count": 4000,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 4001,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "fault\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n31.954  build-script-bu  393094 391145   0 /target/debug/build/rustix-0a16b3d645d9d205/build-script-build\n31.958  cc1              393080 393003   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n31.959  aarch64-linux-g  393090 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n31.969  as               393100 392225   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n31.978  cc1              393101 393090   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n31.980  powerpc64le-lin  393091 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n31.983  as               393105 392947   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n31.985  rustc            393102 393094   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --target powerpc64le-unknown-linux-gnu --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/rustix-2befdd4c145c4aba/out -\n32.003  cc1              393106 393091   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.004  as               393099 392639   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.006  riscv64-linux-g  393089 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.008  as               393112 392856   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.008  powerpc64le-lin  393107 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.023  as               393110 392811   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.024  cc1              393122 393107   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.028  cc1              393120 393089   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.029  aarch64-linux-g  393124 391596   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I ...\n32.031  riscv64-linux-g  393119 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.036  cc1              393127 393124   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.040  rustc            393111 391145   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\" -C metadata=9cf788c8acaa5824 ...\n32.047  riscv64-linux-g  393128 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.054  cc1              393129 393119   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.058  powerpc64le-lin  393131 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.059  aarch64-linux-g  393126 391596   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I ...\n32.068  cc1              393151 393128   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.070  cc1              393149 393131   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.082  as               393154 393009   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.083  cc1              393155 393126   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.087  riscv64-linux-g  393130 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.100  as               393163 393007   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.109  aarch64-linux-g  393157 391596   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I ...\n32.112  rustc            393162 391145   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name log --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"kv_unstable\", \"kv_unstable_serde\", \"kv_unstable_std\", \"kv_unstable_sval\", \"max_level_debug\", \"max_level_err -C metadata=2e4c0c2074165706 ...\n32.121  rustc            393156 391145   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name once_cell --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.18.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"race\" ...\n32.121  as               393167 392970   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.125  cc1              393172 393130   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.125  cc1              393170 393157   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.129  riscv64-linux-g  393165 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.141  build-script-bu  393179 391442   0 /target/debug/build/thiserror-35d5289b9aaf462a/build-script-build\n32.145  as               393182 392946   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.149  cc               393175 392833   0 /tmp/native-trace-389767-1783994316079/shims/cc -m64 /target/debug/build/pprof-003116af80e26532/rustcGM7Aer/symbols.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.1ommwjucy2p2mxqxvsktyrpze.0jdd3qc.rcgu.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.29slsntdpaa1mktrjctdmljuw.0jdd3qc.rcgu.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.4vfyzww6v0hzwd14b5gr4eabh.0jdd3qc.rcgu.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.acvu3wu45refsrqvepeowcxo9.0jdd3qc.rcgu.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.bq5mix0lyggzrmcn3ggar52nx.0jdd3qc.rcgu.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.0p081agfvz5y9w1262jx27ymq.0jdd3qc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n32.150  cc1              393181 393165   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.154  rustc            393173 391442   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bitflags --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"default\", \"example_generated\", \"rustc-dep-of-std\")) ...\n32.158  aarch64-linux-g  393168 391596   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I ...\n32.158  riscv64-linux-g  393180 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.162  as               393186 391983   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x509_def.o /tmp/ccWAD3R7.s\n32.168  cc               393185 393175   0 /usr/bin/cc -m64 /target/debug/build/pprof-003116af80e26532/rustcGM7Aer/symbols.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.1ommwjucy2p2mxqxvsktyrpze.0jdd3qc.rcgu.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.29slsntdpaa1mktrjctdmljuw.0jdd3qc.rcgu.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.4vfyzww6v0hzwd14b5gr4eabh.0jdd3qc.rcgu.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.acvu3wu45refsrqvepeowcxo9.0jdd3qc.rcgu.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.bq5mix0lyggzrmcn3ggar52nx.0jdd3qc.rcgu.o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532.0p081agfvz5y9w1262jx27ymq.0jdd3qc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n32.171  cc1              393192 393168   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.175  rustc            393187 393179   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2018 --crate-name=thiserror_build --crate-type=lib --emit=metadata --out-dir /target/riscv64gc-unknown-linux-gnu/debug/build/thiserror-01a6b7c7d901c723/out /target/riscv64gc-unknown-linux-gnu/debug/build/thiserror-01a6b7c7d901c723/out/probe.rs --target riscv64gc-unknown-linux-gnu\n32.180  riscv64-linux-g  393189 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.180  aarch64-linux-g  393188 391596   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I ...\n32.184  as               393190 392922   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.187  powerpc64le-lin  393191 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.188  as               393195 392924   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.193  as               393201 393083   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.193  cc1              393194 393180   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.195  aarch64-linux-g  393196 391596   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I ...\n32.197  collect2         393202 393185   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccN5tdEu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n32.197  riscv64-linux-g  393198 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.203  cc1              393199 393188   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.207  cc1              393207 393191   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.208  cc1              393197 393189   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.213  aarch64-linux-g  393204 391596   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I ...\n32.220  ld.lld           393214 393202   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccN5tdEu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/pprof-003116af80e26532/build_script_build-003116af80e26532 ...\n32.223  rust-lld         393214 393202   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccN5tdEu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n32.225  cc1              393208 393196   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.225  aarch64-linux-g  393210 391596   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I ...\n32.225  cc1              393205 393198   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.227  powerpc64le-lin  393203 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.238  cc1              393221 393203   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.239  as               393218 392906   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.240  cc1              393217 393210   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.242  cc               393206 391525   0 /tmp/native-trace-389767-1783994316079/shims/cc -m64 /target/debug/build/libc-718da79730189469/rustcrNL14W/symbols.o /target/debug/build/libc-718da79730189469/build_script_build-718da79730189469.build_script_build.3d64921cd6e2fc3f-cgu.0.rcgu.o /target/debug/build/libc-718da79730189469/build_script_build-718da79730189469.build_script_build.3d64921cd6e2fc3f-cgu.1.rcgu.o /target/debug/build/libc-718da79730189469/build_script_build-718da79730189469.ckhy8b61128catfiydh0j3gqp.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n32.243  cc1              393215 393204   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.243  as               393220 393052   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.250  as               393222 392931   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.251  powerpc64le-lin  393216 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.257  as               393224 392867   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.266  riscv64-linux-g  393211 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.269  rustc            393209 390978   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lock_api-0.4.10/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"atomic_usize\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n32.275  as               393231 392993   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.277  cc1              393234 393211   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.278  as               393227 392821   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.286  as               393232 392968   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.299  as               393237 393089   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.299  as               393235 392910   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.299  as               393238 392920   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.300  cc               393230 393206   0 /usr/bin/cc -m64 /target/debug/build/libc-718da79730189469/rustcrNL14W/symbols.o /target/debug/build/libc-718da79730189469/build_script_build-718da79730189469.build_script_build.3d64921cd6e2fc3f-cgu.0.rcgu.o /target/debug/build/libc-718da79730189469/build_script_build-718da79730189469.build_script_build.3d64921cd6e2fc3f-cgu.1.rcgu.o /target/debug/build/libc-718da79730189469/build_script_build-718da79730189469.ckhy8b61128catfiydh0j3gqp.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n32.301  as               393236 393003   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.305  cc1              393228 393216   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.310  powerpc64le-lin  393244 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.311  riscv64-linux-g  393229 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.314  as               393243 392997   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.319  rustc            393226 391145   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name object --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/object-0.31.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"archive\" --cfg feature=\"coff\" --cfg feature=\"elf\" ...\n32.321  cc1              393256 393244   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.327  as               393266 392999   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.327  as               393246 393041   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.330  cc1              393248 393229   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.339  collect2         393276 393230   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDN9JsG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n32.341  powerpc64le-lin  393253 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.359  aarch64-linux-g  393277 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n32.360  as               393289 393031   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.360  as               393290 393107   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.360  cc1              393284 393253   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.363  rustc            393281 390978   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name object --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/object-0.31.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"archive\" --cfg feature=\"coff\" --cfg feature=\"elf\" ...\n32.370  ld.lld           393292 393276   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDN9JsG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-718da79730189469/build_script_build-718da79730189469 ...\n32.378  cc1              393291 393277   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n32.379  powerpc64le-lin  393282 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.387  build-script-bu  393298 390978   0 /target/debug/build/rustix-0a16b3d645d9d205/build-script-build\n32.387  rust-lld         393292 393276   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDN9JsG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n32.390  powerpc64le-lin  393296 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.397  build-script-bu  393288 390978   0 /target/debug/build/cpp_demangle-74990a41cb4e36c9/build-script-build\n32.404  powerpc64le-lin  393300 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.404  cc1              393301 393282   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.411  rustc            393299 393298   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --target aarch64-unknown-linux-gnu --out-dir /target/aarch64-unknown-linux-gnu/debug/build/rustix-f23dfed64fb951b9/out -\n32.412  cc1              393305 393300   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.427  cc1              393306 393296   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.429  as               393311 393211   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.437  riscv64-linux-g  393310 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.439  powerpc64le-lin  393309 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.442  cc1              393317 393310   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.446  as               393313 392954   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.446  riscv64-linux-g  393318 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.456  as               393320 393126   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.456  cc1              393327 393309   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.458  as               393322 393091   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.460  cc1              393330 393318   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.463  powerpc64le-lin  393321 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.463  as               393329 393203   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.474  as               393334 393165   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.484  riscv64-linux-g  393328 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.491  as               393339 392729   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x509_txt.o /tmp/ccPJJcex.s\n32.495  cc1              393337 393321   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.498  as               393343 393168   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.500  cc               393335 391205   0 /tmp/native-trace-389692-1783994315897/shims/cc -m64 /target/debug/build/cpp_demangle-74990a41cb4e36c9/rustcPI0P9H/symbols.o /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.build_script_build.c55557ca43dcbfdc-cgu.0. /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.build_script_build.c55557ca43dcbfdc-cgu.1. /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.build_script_build.c55557ca43dcbfdc-cgu.2. /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.build_script_build.c55557ca43dcbfdc-cgu.3. /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.build_script_build.c55557ca43dcbfdc-cgu.4. /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.21jqvq05iyeumrh72nepedxol.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n32.500  as               393344 393180   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.504  powerpc64le-lin  393333 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.504  riscv64-linux-g  393338 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.505  as               393340 393024   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.508  cc1              393341 393328   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.518  cc1              393351 393338   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.527  cc               393350 393335   0 /usr/bin/cc -m64 /target/debug/build/cpp_demangle-74990a41cb4e36c9/rustcPI0P9H/symbols.o /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.build_script_build.c55557ca43dcbfdc-cgu.0. /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.build_script_build.c55557ca43dcbfdc-cgu.1. /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.build_script_build.c55557ca43dcbfdc-cgu.2. /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.build_script_build.c55557ca43dcbfdc-cgu.3. /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.build_script_build.c55557ca43dcbfdc-cgu.4. /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9.21jqvq05iyeumrh72nepedxol.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n32.534  as               393370 392929   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.539  powerpc64le-lin  393346 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.541  riscv64-linux-g  393349 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.544  as               393372 392422   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x509_req.o /tmp/ccV1HQgh.s\n32.549  collect2         393373 393350   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnGnk3t.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n32.556  cc1              393377 393346   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.559  cc1              393347 393333   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.561  cc1              393380 393349   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.561  as               393345 393131   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.568  as               393383 392728   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.571  ld.lld           393381 393373   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnGnk3t.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/cpp_demangle-74990a41cb4e36c9/build_script_build-74990a41cb4e36c9 ...\n32.575  as               393384 393198   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.576  as               393386 393119   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.579  rustc            393312 390978   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cpp_demangle --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n32.585  powerpc64le-lin  393379 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.586  aarch64-linux-g  393387 391596   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I ...\n"
    },
    {
      "argv": [
        "/target/debug/build/ash-18b97227eb4289a8/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 380793,
      "build_script_target_dir": "ash-18b97227eb4289a8",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/ash-18b97227eb4289a8/build-script-build",
      "pid": 380793,
      "ppid": 380715,
      "root_cargo_pid": 380715,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "ash",
      "cwd": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
      "event_id": "bsrun:89be77ac998fe6f8:f1d2e4686d87d918:2a08caf2034bc188",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/ash-18b97227eb4289a8/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
      "out_dir": "/target/debug/build/ash-18b97227eb4289a8/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
      "success": true,
      "target": null,
      "version": "0.38.0+1.3.281",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-aarch64-5htp0yli/src/ash-0.38.0+1.3.281",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
  "item": {
    "rank": 1657,
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "crate_id": "7518",
    "version_id": "1100484",
    "downloads": 9690210,
    "cumulative_downloads": 98856109117,
    "cumulative_share_of_global": 0.3696001704808082,
    "status": "ok",
    "has_build_script": true,
    "build_script_path": "build.rs",
    "build_script_exists": true,
    "package_build_field": null,
    "build_script_reason": "default_build_rs_exists",
    "download_source": "local"
  }
}
```
