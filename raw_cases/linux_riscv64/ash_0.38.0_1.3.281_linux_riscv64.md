# `ash` `0.38.0+1.3.281`

Platform: Linux riscv64

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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl",
    "/target/debug/build/ash-18b97227eb4289a8",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "/lib/x86_64-linux-gnu",
    "/lib64"
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1",
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
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/libc.so.6",
      "source": "link_trace"
    },
    {
      "directory": "/lib64",
      "kind": "dynamic_library",
      "path": "/lib64/ld-linux-x86-64.so.2",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o",
      "source": "link_trace"
    }
  ],
  "kind": "resolved_link",
  "map_path": "/tmp/native-trace-link-cc-381044-1783994293043838698.map",
  "pid": 381044,
  "ppid": 380987,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-381044-1783994293043838698.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
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
  "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "workspace_root": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281"
  ],
  "packages": [
    {
      "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
      "name": "ash",
      "version": "0.38.0+1.3.281",
      "manifest_path": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281"
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
    "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "exit_code": 0,
  "kind": "exec",
  "pid": 381044,
  "ppid": 380987,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "event_id": "used:cc:89b86a62730b26dc:cc630cce00b0e015:b60e9cb133a16581",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
  "path": "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
  "pid": 381044,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "event_id": "used:cc:89b86a62730b26dc:5dfc2ef3a60074a8:b60e9cb133a16581",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
  "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
  "pid": 381044,
  "sha256": "2a16b8eb5c24abf28fe0708e273308c5311d5227b33c207e0bab24b19abfbd17",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "event_id": "used:cc:89b86a62730b26dc:6dea200df7f28954:b60e9cb133a16581",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
  "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
  "pid": 381044,
  "sha256": "8b98d3af405eb9e2e4ce88b44f9fe23b1c58809a615b9442743ac83be5399b47",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "event_id": "used:cc:89b86a62730b26dc:15ccdff842239b39:b60e9cb133a16581",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
  "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
  "pid": 381044,
  "sha256": "d42d39311602dec28825831e6c05164466b58f9cf8c661d242289a5242a5d291",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "event_id": "used:cc:89b86a62730b26dc:ea7566bcd3daf28b:b60e9cb133a16581",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
  "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
  "pid": 381044,
  "sha256": "ef606e5ec528b1659cdd67453b931aa4918f0493598f8b3feae89f39e8d77899",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "event_id": "used:cc:89b86a62730b26dc:573d5502c624fe0b:b60e9cb133a16581",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
  "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
  "pid": 381044,
  "sha256": "24feb63398247fc7b089397eb814e45bc7f8099032de68962eaa177151f638b9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "event_id": "used:cc:89b86a62730b26dc:e1b4834724f2dc96:b60e9cb133a16581",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
  "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
  "pid": 381044,
  "sha256": "286f1094277661a0dec8686a6ad6da3271263c9fb5556b73cf3ed1a107729102",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "cargo_pkg_name": "ash",
  "cargo_pkg_version": "0.38.0+1.3.281",
  "context_path": "/tmp/native-trace-380317-1783994290434/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-380317-1783994290434/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 381044,
  "ppid": 380987,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
    "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl",
    "/target/debug/build/ash-18b97227eb4289a8",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "/lib/x86_64-linux-gnu",
    "/lib64"
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ash-18b97227eb4289a8",
      "kind": "object",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1",
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
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/libc.so.6",
      "source": "link_trace"
    },
    {
      "directory": "/lib64",
      "kind": "dynamic_library",
      "path": "/lib64/ld-linux-x86-64.so.2",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o",
      "source": "link_trace"
    }
  ],
  "kind": "resolved_link",
  "map_path": "/tmp/native-trace-link-cc-381044-1783994293043838698.map",
  "pid": 381044,
  "ppid": 380987,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-381044-1783994293043838698.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
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
  "parse_error_count": 2,
  "parsed_event_count": 4208,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 4210,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "zma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.617  powerpc64le-lin  393607 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.622  containerd-shim  393590 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 74c995cacc08c0c4f866246cc016fc56612fb2b641b063a53d54cba058da59e2 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/74c995cacc08c0c4f866246cc016fc56612fb2b641b063a53d54cba058d delete\n32.629  runc             393629 393590   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/74c995cacc08c0c4f866246cc016fc56612fb2b641b063a53d54cba058da59e --log-format json delete --force 74c995cacc08c0c4f866246cc016fc56612fb2b641b063a53d54cba058da59e2\n32.633  rustc            393615 391442   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"extra_traits\" --cfg feature=\"std\" ...\n32.633  riscv64-linux-g  393579 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.649  as               393584 393463   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.653  riscv64-linux-g  393634 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.657  cc1              393621 393607   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.658  cc1              393635 393579   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.660  as               393641 393456   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.661  as               393639 393535   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.661  cc1              393602 393597   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n32.673  build-script-bu  393640 391145   0 /target/debug/build/cpp_demangle-74990a41cb4e36c9/build-script-build\n32.674  riscv64-linux-g  393638 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.684  cc1              393653 393638   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.685  as               393648 392541   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x509_trs.o /tmp/ccTCJaQk.s\n32.685  as               393657 393481   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.690  as               393652 393475   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.693  as               393659 393333   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.694  cc1              393654 393634   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.694  riscv64-linux-g  393649 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.698  powerpc64le-lin  393651 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.701  aarch64-linux-g  393647 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n32.705  cc1              393662 393649   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.707  rustc            393658 391145   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cpp_demangle --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n32.707  as               393661 392521   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x509_set.o /tmp/ccPMi3fM.s\n32.714  rustc            393655 393613   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name probe0 --crate-type=lib --out-dir /target/aarch64-unknown-linux-gnu/debug/build/lock_api-4efdabf64c8e39d5/out --emit=llvm-ir --target aarch64-unknown-linux-gnu -\n32.717  as               393665 393496   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.724  cc1              393678 393651   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.729  sh               393688 393676   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethd75c1c4\n32.730  rustc            393664 391442   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lock_api-0.4.10/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"atomic_usize\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n32.731  as               393675 393506   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.731  ethtool          393690 393688   0 /usr/sbin/ethtool -i vethd75c1c4\n32.733  riscv64-linux-g  393660 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.733  sed              393691 393688   0 /usr/bin/sed -n s/^driver: //p\n32.741  cc1              393695 393660   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.741  powerpc64le-lin  393687 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.748  systemd-sysctl   393697 393676   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd75c1c4 --prefix=/net/ipv4/neigh/vethd75c1c4 --prefix=/net/ipv6/conf/vethd75c1c4 --prefix=/net/ipv6/neigh/vethd75c1c4\n32.749  cc1              393698 393687   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.751  as               393699 393300   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.757  powerpc64le-lin  393696 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.759  riscv64-linux-g  393693 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.767  cc1              393700 393647   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n32.784  cc1              393704 393696   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.786  cc1              393705 393693   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.793  as               393710 393524   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.797  as               393711 393651   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.799  powerpc64le-lin  393702 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.804  as               393715 393124   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.807  riscv64-linux-g  393708 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.815  as               393716 393379   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.828  cc1              393722 393702   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.834  cc1              393718 393708   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.840  as               393726 393490   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.845  as               393727 393349   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.872  as               393731 393498   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.883  as               393725 393189   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.886  powerpc64le-lin  393712 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.901  build-script-bu  393745 391442   0 /target/debug/build/rustix-0a16b3d645d9d205/build-script-build\n32.901  as               393742 393593   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.901  powerpc64le-lin  393747 392289   0 \n32.907  rustc            393748 390978   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name lock_api --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lock_api-0.4.10/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"atomic_usize\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n32.922  as               393752 393581   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.923  riscv64-linux-g  393754 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.923  powerpc64le-lin  393751 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.924  as               393757 393450   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.927  as               393750 393634   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.930  cc               393749 393664   0 /tmp/native-trace-389767-1783994316079/shims/cc -m64 /target/debug/build/lock_api-2503a189a9387e15/rustcmVQIWq/symbols.o /target/debug/build/lock_api-2503a189a9387e15/build_script_build-2503a189a9387e15.build_script_build.41a060351a2c0fcc-cgu.0.rcgu /target/debug/build/lock_api-2503a189a9387e15/build_script_build-2503a189a9387e15.dm7omear61ihnhvk00ta19kqz.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-55afc35e88511a79.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n32.930  as               393755 393416   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.933  cc1              393756 393712   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.935  cc1              393759 393754   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.943  cc               393764 393749   0 /usr/bin/cc -m64 /target/debug/build/lock_api-2503a189a9387e15/rustcmVQIWq/symbols.o /target/debug/build/lock_api-2503a189a9387e15/build_script_build-2503a189a9387e15.build_script_build.41a060351a2c0fcc-cgu.0.rcgu /target/debug/build/lock_api-2503a189a9387e15/build_script_build-2503a189a9387e15.dm7omear61ihnhvk00ta19kqz.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-55afc35e88511a79.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n32.951  riscv64-linux-g  393758 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.955  as               393770 393638   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.966  collect2         393775 393764   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBgwEhe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n32.969  as               393772 393424   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.969  cc1              393753 393747   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.972  as               393767 393451   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x_all.o /tmp/ccBvzAA5.s\n32.979  cc1              393771 393758   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.980  cc1              393763 393751   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.981  as               393780 393090   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x509spki.o /tmp/ccDIMxEP.s\n32.983  rustc            393773 393745   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --target riscv64gc-unknown-linux-gnu --out-dir /target/riscv64gc-unknown-linux-gnu/debug/build/rustix-7b7eb109ccfb161a/out -\n32.986  as               393777 393346   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.992  build-script-bu  393738 391442   0 /target/debug/build/libc-5bfb1d0be98543ad/build-script-build\n32.999  ld.lld           393778 393775   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBgwEhe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/lock_api-2503a189a9387e15/build_script_build-2503a189a9387e15 ...\n33.004  as               393781 393754   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.011  as               393782 393708   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.033  as               393785 393410   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.034  rustc            393784 393738   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n33.036  rust-lld         393778 393775   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBgwEhe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n33.049  as               393787 392754   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x509_v3.o /tmp/ccV6Y9Lr.s\n33.051  as               393786 393597   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x_exten.o /tmp/cc5a3Vha.s\n33.060  as               393804 393579   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.068  as               393805 393465   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.081  cc               393806 393582   0 /tmp/native-trace-389692-1783994315897/shims/cc -m64 /target/debug/build/lock_api-2503a189a9387e15/rustcbTf3fl/symbols.o /target/debug/build/lock_api-2503a189a9387e15/build_script_build-2503a189a9387e15.build_script_build.41a060351a2c0fcc-cgu.0.rcgu /target/debug/build/lock_api-2503a189a9387e15/build_script_build-2503a189a9387e15.dm7omear61ihnhvk00ta19kqz.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-55afc35e88511a79.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n33.085  as               393807 393045   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.088  as               393808 393712   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.089  cc               393809 393806   0 /usr/bin/cc -m64 /target/debug/build/lock_api-2503a189a9387e15/rustcbTf3fl/symbols.o /target/debug/build/lock_api-2503a189a9387e15/build_script_build-2503a189a9387e15.build_script_build.41a060351a2c0fcc-cgu.0.rcgu /target/debug/build/lock_api-2503a189a9387e15/build_script_build-2503a189a9387e15.dm7omear61ihnhvk00ta19kqz.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-55afc35e88511a79.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n33.096  as               393812 393321   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.097  collect2         393811 393809   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccow39P9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n33.102  as               393813 393378   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.116  aarch64-linux-g  393810 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n33.126  ld.lld           393814 393811   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccow39P9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/lock_api-2503a189a9387e15/build_script_build-2503a189a9387e15 ...\n33.131  rust-lld         393814 393811   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccow39P9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n33.138  cc1              393820 393810   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n33.146  aarch64-linux-g  393819 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n33.152  aarch64-linux-g  393824 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n33.154  cc1              393825 393819   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n33.160  as               393828 393693   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.160  cc1              393829 393824   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n33.160  aarch64-linux-g  393827 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n33.165  as               393826 393607   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.169  as               393832 393702   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.177  as               393834 393660   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.187  cc1              393830 393827   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n33.207  as               393833 393649   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.238  rustc            393855 390978   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"parallel\")) -C metadata=4c7e619b6086f133 ...\n33.240  as               393860 393687   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.250  rustc            393858 391442   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rustix --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.14/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"fs\" ...\n33.276  as               393863 393696   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.276  as               393873 393758   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.287  aarch64-linux-g  393874 391596   0 /usr/bin/aarch64-linux-gnu-ar cq /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/liblzma.a /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/0b27bbdc3d149821-tuklib_cpucores.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/0b27bbdc3d149821-tuklib_physmem.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/9958957cfa71505a-check.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/9958957cfa71505a-crc32_fast.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/9958957cfa71505a-crc64_fast.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/9958957cfa71505a-sha256.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-alone_decoder.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-alone_encoder.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-auto_decoder.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-block_buffer_decoder.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-block_buffer_encoder.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-block_decoder.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-block_encoder.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-block_header_decoder.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-block_header_encoder.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-block_util.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-common.o ...\n33.293  rustc            393872 391442   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\" -C metadata=9cf788c8acaa5824 ...\n33.308  aarch64-linux-g  393867 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n33.312  as               393877 393747   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.316  cc1              393878 393867   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n33.319  aarch64-linux-g  393880 391596   0 /usr/bin/aarch64-linux-gnu-ar s /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/liblzma.a\n33.321  as               393882 393433   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.325  as               393883 393751   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.329  aarch64-linux-g  393879 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n33.342  cc1              393885 393879   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n33.365  rustc            393892 389621   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name liblzma_sys --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"bindgen\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n33.368  as               393893 392290   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x509_lu.o /tmp/ccBdktFl.s\n33.373  as               393895 393393   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.386  riscv64-linux-g  393901 392425   0 /usr/bin/riscv64-linux-gnu-ar cq /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/liblzma.a /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/0b27bbdc3d149821-tuklib_cpucores.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/0b27bbdc3d149821-tuklib_physmem.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/9958957cfa71505a-check.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/9958957cfa71505a-crc32_fast.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/9958957cfa71505a-crc64_fast.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/9958957cfa71505a-sha256.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-alone_decoder.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-alone_encoder.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-auto_decoder.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-block_buffer_decoder.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-block_buffer_encoder.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-block_decoder.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-block_encoder.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-block_header_decoder.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-block_header_encoder.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-block_util.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-common.o ...\n33.400  build-script-bu  393897 391145   0 /target/debug/build/lock_api-2503a189a9387e15/build-script-build\n33.410  as               393902 392995   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x509name.o /tmp/ccYFe8UF.s\n33.415  rustc            393903 393897   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n33.427  as               393905 392934   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x509_vpm.o /tmp/ccbuS902.s\n"
}
```

#### Record 15

```json
{
  "argv": [
    "/target/debug/build/ash-18b97227eb4289a8/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 381125,
  "build_script_target_dir": "ash-18b97227eb4289a8",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/ash-18b97227eb4289a8/build-script-build",
  "pid": 381125,
  "ppid": 380958,
  "root_cargo_pid": 380958,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "_build_script_out_dir": "/target/debug/build/ash-18b97227eb4289a8/out"
}
```

#### Record 16

```json
{
  "crate": "ash",
  "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "event_id": "bsrun:6c83fa2429188748:f1d2e4686d87d918:2a08caf2034bc188",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/ash-18b97227eb4289a8/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
  "out_dir": "/target/debug/build/ash-18b97227eb4289a8/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
  "success": true,
  "target": null,
  "version": "0.38.0+1.3.281",
  "_owner": {
    "crate": "ash",
    "version": "0.38.0+1.3.281",
    "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
    "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
    "source": "cwd_prefix"
  }
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T01:58:46.820059+00:00",
  "crate": "ash",
  "version": "0.38.0+1.3.281",
  "architecture": "riscv64",
  "duration_seconds": 40.4817860070616,
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
        "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
        "manifest_path": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281/Cargo.toml"
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
      "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
      "workspace_root": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281"
      ],
      "packages": [
        {
          "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
          "name": "ash",
          "version": "0.38.0+1.3.281",
          "manifest_path": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281"
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
        "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
      "exit_code": 0,
      "kind": "exec",
      "pid": 381044,
      "ppid": 380987,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
      "event_id": "used:cc:89b86a62730b26dc:cc630cce00b0e015:b60e9cb133a16581",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
      "path": "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
      "pid": 381044,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
      "event_id": "used:cc:89b86a62730b26dc:5dfc2ef3a60074a8:b60e9cb133a16581",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
      "pid": 381044,
      "sha256": "2a16b8eb5c24abf28fe0708e273308c5311d5227b33c207e0bab24b19abfbd17",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
      "event_id": "used:cc:89b86a62730b26dc:6dea200df7f28954:b60e9cb133a16581",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
      "pid": 381044,
      "sha256": "8b98d3af405eb9e2e4ce88b44f9fe23b1c58809a615b9442743ac83be5399b47",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
      "event_id": "used:cc:89b86a62730b26dc:15ccdff842239b39:b60e9cb133a16581",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
      "pid": 381044,
      "sha256": "d42d39311602dec28825831e6c05164466b58f9cf8c661d242289a5242a5d291",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
      "event_id": "used:cc:89b86a62730b26dc:ea7566bcd3daf28b:b60e9cb133a16581",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
      "pid": 381044,
      "sha256": "ef606e5ec528b1659cdd67453b931aa4918f0493598f8b3feae89f39e8d77899",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
      "event_id": "used:cc:89b86a62730b26dc:573d5502c624fe0b:b60e9cb133a16581",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
      "pid": 381044,
      "sha256": "24feb63398247fc7b089397eb814e45bc7f8099032de68962eaa177151f638b9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
      "event_id": "used:cc:89b86a62730b26dc:e1b4834724f2dc96:b60e9cb133a16581",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8",
      "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
      "pid": 381044,
      "sha256": "286f1094277661a0dec8686a6ad6da3271263c9fb5556b73cf3ed1a107729102",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
      "cargo_pkg_name": "ash",
      "cargo_pkg_version": "0.38.0+1.3.281",
      "context_path": "/tmp/native-trace-380317-1783994290434/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-380317-1783994290434/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 381044,
      "ppid": 380987,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
        "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl",
        "/target/debug/build/ash-18b97227eb4289a8",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "/lib/x86_64-linux-gnu",
        "/lib64"
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/11",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl",
          "kind": "object",
          "path": "/target/debug/build/ash-18b97227eb4289a8/rustcj77xgl/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ash-18b97227eb4289a8",
          "kind": "object",
          "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.1mw9xgaykkw9nz1ut5vdv3uaw.0z4kzd3.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ash-18b97227eb4289a8",
          "kind": "object",
          "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.3mheg1tbtii0xq0yjfssplije.0z4kzd3.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ash-18b97227eb4289a8",
          "kind": "object",
          "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.62c0bsu1twm3dgx0ns0xs0crz.0z4kzd3.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ash-18b97227eb4289a8",
          "kind": "object",
          "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.95ucn68qkxco9aiq07nlbzfor.0z4kzd3.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ash-18b97227eb4289a8",
          "kind": "object",
          "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.anfx49k3r45deqpp6do7hsnfz.0z4kzd3.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ash-18b97227eb4289a8",
          "kind": "object",
          "path": "/target/debug/build/ash-18b97227eb4289a8/build_script_build-18b97227eb4289a8.6r6ak93wceb86d6w1u2ylnj62.0z4kzd3.rcgu.o",
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
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1",
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
          "directory": "/lib/x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/lib/x86_64-linux-gnu/libc.so.6",
          "source": "link_trace"
        },
        {
          "directory": "/lib64",
          "kind": "dynamic_library",
          "path": "/lib64/ld-linux-x86-64.so.2",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/11",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o",
          "source": "link_trace"
        }
      ],
      "kind": "resolved_link",
      "map_path": "/tmp/native-trace-link-cc-381044-1783994293043838698.map",
      "pid": 381044,
      "ppid": 380987,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-381044-1783994293043838698.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
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
      "parse_error_count": 2,
      "parsed_event_count": 4208,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 4210,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "zma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.617  powerpc64le-lin  393607 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.622  containerd-shim  393590 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 74c995cacc08c0c4f866246cc016fc56612fb2b641b063a53d54cba058da59e2 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/74c995cacc08c0c4f866246cc016fc56612fb2b641b063a53d54cba058d delete\n32.629  runc             393629 393590   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/74c995cacc08c0c4f866246cc016fc56612fb2b641b063a53d54cba058da59e --log-format json delete --force 74c995cacc08c0c4f866246cc016fc56612fb2b641b063a53d54cba058da59e2\n32.633  rustc            393615 391442   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"extra_traits\" --cfg feature=\"std\" ...\n32.633  riscv64-linux-g  393579 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.649  as               393584 393463   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.653  riscv64-linux-g  393634 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.657  cc1              393621 393607   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.658  cc1              393635 393579   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.660  as               393641 393456   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.661  as               393639 393535   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.661  cc1              393602 393597   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n32.673  build-script-bu  393640 391145   0 /target/debug/build/cpp_demangle-74990a41cb4e36c9/build-script-build\n32.674  riscv64-linux-g  393638 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.684  cc1              393653 393638   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.685  as               393648 392541   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x509_trs.o /tmp/ccTCJaQk.s\n32.685  as               393657 393481   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.690  as               393652 393475   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.693  as               393659 393333   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.694  cc1              393654 393634   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.694  riscv64-linux-g  393649 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.698  powerpc64le-lin  393651 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.701  aarch64-linux-g  393647 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n32.705  cc1              393662 393649   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.707  rustc            393658 391145   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cpp_demangle --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n32.707  as               393661 392521   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x509_set.o /tmp/ccPMi3fM.s\n32.714  rustc            393655 393613   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name probe0 --crate-type=lib --out-dir /target/aarch64-unknown-linux-gnu/debug/build/lock_api-4efdabf64c8e39d5/out --emit=llvm-ir --target aarch64-unknown-linux-gnu -\n32.717  as               393665 393496   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.724  cc1              393678 393651   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.729  sh               393688 393676   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethd75c1c4\n32.730  rustc            393664 391442   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lock_api-0.4.10/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"atomic_usize\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n32.731  as               393675 393506   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.731  ethtool          393690 393688   0 /usr/sbin/ethtool -i vethd75c1c4\n32.733  riscv64-linux-g  393660 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.733  sed              393691 393688   0 /usr/bin/sed -n s/^driver: //p\n32.741  cc1              393695 393660   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.741  powerpc64le-lin  393687 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.748  systemd-sysctl   393697 393676   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd75c1c4 --prefix=/net/ipv4/neigh/vethd75c1c4 --prefix=/net/ipv6/conf/vethd75c1c4 --prefix=/net/ipv6/neigh/vethd75c1c4\n32.749  cc1              393698 393687   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.751  as               393699 393300   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.757  powerpc64le-lin  393696 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.759  riscv64-linux-g  393693 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.767  cc1              393700 393647   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n32.784  cc1              393704 393696   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.786  cc1              393705 393693   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.793  as               393710 393524   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.797  as               393711 393651   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.799  powerpc64le-lin  393702 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.804  as               393715 393124   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.807  riscv64-linux-g  393708 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.815  as               393716 393379   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.828  cc1              393722 393702   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.834  cc1              393718 393708   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.840  as               393726 393490   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.845  as               393727 393349   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.872  as               393731 393498   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.883  as               393725 393189   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.886  powerpc64le-lin  393712 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.901  build-script-bu  393745 391442   0 /target/debug/build/rustix-0a16b3d645d9d205/build-script-build\n32.901  as               393742 393593   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.901  powerpc64le-lin  393747 392289   0 \n32.907  rustc            393748 390978   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name lock_api --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lock_api-0.4.10/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"atomic_usize\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n32.922  as               393752 393581   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.923  riscv64-linux-g  393754 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.923  powerpc64le-lin  393751 392289   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta ...\n32.924  as               393757 393450   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.927  as               393750 393634   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.930  cc               393749 393664   0 /tmp/native-trace-389767-1783994316079/shims/cc -m64 /target/debug/build/lock_api-2503a189a9387e15/rustcmVQIWq/symbols.o /target/debug/build/lock_api-2503a189a9387e15/build_script_build-2503a189a9387e15.build_script_build.41a060351a2c0fcc-cgu.0.rcgu /target/debug/build/lock_api-2503a189a9387e15/build_script_build-2503a189a9387e15.dm7omear61ihnhvk00ta19kqz.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-55afc35e88511a79.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n32.930  as               393755 393416   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.933  cc1              393756 393712   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.935  cc1              393759 393754   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.943  cc               393764 393749   0 /usr/bin/cc -m64 /target/debug/build/lock_api-2503a189a9387e15/rustcmVQIWq/symbols.o /target/debug/build/lock_api-2503a189a9387e15/build_script_build-2503a189a9387e15.build_script_build.41a060351a2c0fcc-cgu.0.rcgu /target/debug/build/lock_api-2503a189a9387e15/build_script_build-2503a189a9387e15.dm7omear61ihnhvk00ta19kqz.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-55afc35e88511a79.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n32.951  riscv64-linux-g  393758 392425   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I ...\n32.955  as               393770 393638   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.966  collect2         393775 393764   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBgwEhe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n32.969  as               393772 393424   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.969  cc1              393753 393747   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.972  as               393767 393451   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x_all.o /tmp/ccBvzAA5.s\n32.979  cc1              393771 393758   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.980  cc1              393763 393751   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common ...\n32.981  as               393780 393090   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x509spki.o /tmp/ccDIMxEP.s\n32.983  rustc            393773 393745   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --target riscv64gc-unknown-linux-gnu --out-dir /target/riscv64gc-unknown-linux-gnu/debug/build/rustix-7b7eb109ccfb161a/out -\n32.986  as               393777 393346   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n32.992  build-script-bu  393738 391442   0 /target/debug/build/libc-5bfb1d0be98543ad/build-script-build\n32.999  ld.lld           393778 393775   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBgwEhe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/lock_api-2503a189a9387e15/build_script_build-2503a189a9387e15 ...\n33.004  as               393781 393754   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.011  as               393782 393708   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.033  as               393785 393410   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.034  rustc            393784 393738   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n33.036  rust-lld         393778 393775   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBgwEhe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n33.049  as               393787 392754   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x509_v3.o /tmp/ccV6Y9Lr.s\n33.051  as               393786 393597   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x_exten.o /tmp/cc5a3Vha.s\n33.060  as               393804 393579   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.068  as               393805 393465   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.081  cc               393806 393582   0 /tmp/native-trace-389692-1783994315897/shims/cc -m64 /target/debug/build/lock_api-2503a189a9387e15/rustcbTf3fl/symbols.o /target/debug/build/lock_api-2503a189a9387e15/build_script_build-2503a189a9387e15.build_script_build.41a060351a2c0fcc-cgu.0.rcgu /target/debug/build/lock_api-2503a189a9387e15/build_script_build-2503a189a9387e15.dm7omear61ihnhvk00ta19kqz.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-55afc35e88511a79.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n33.085  as               393807 393045   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.088  as               393808 393712   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.089  cc               393809 393806   0 /usr/bin/cc -m64 /target/debug/build/lock_api-2503a189a9387e15/rustcbTf3fl/symbols.o /target/debug/build/lock_api-2503a189a9387e15/build_script_build-2503a189a9387e15.build_script_build.41a060351a2c0fcc-cgu.0.rcgu /target/debug/build/lock_api-2503a189a9387e15/build_script_build-2503a189a9387e15.dm7omear61ihnhvk00ta19kqz.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-55afc35e88511a79.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n33.096  as               393812 393321   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.097  collect2         393811 393809   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccow39P9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n33.102  as               393813 393378   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.116  aarch64-linux-g  393810 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n33.126  ld.lld           393814 393811   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccow39P9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/lock_api-2503a189a9387e15/build_script_build-2503a189a9387e15 ...\n33.131  rust-lld         393814 393811   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccow39P9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n33.138  cc1              393820 393810   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n33.146  aarch64-linux-g  393819 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n33.152  aarch64-linux-g  393824 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n33.154  cc1              393825 393819   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n33.160  as               393828 393693   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.160  cc1              393829 393824   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n33.160  aarch64-linux-g  393827 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n33.165  as               393826 393607   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.169  as               393832 393702   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.177  as               393834 393660   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.187  cc1              393830 393827   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n33.207  as               393833 393649   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.238  rustc            393855 390978   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"parallel\")) -C metadata=4c7e619b6086f133 ...\n33.240  as               393860 393687   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.250  rustc            393858 391442   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rustix --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.14/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"fs\" ...\n33.276  as               393863 393696   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.276  as               393873 393758   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.287  aarch64-linux-g  393874 391596   0 /usr/bin/aarch64-linux-gnu-ar cq /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/liblzma.a /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/0b27bbdc3d149821-tuklib_cpucores.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/0b27bbdc3d149821-tuklib_physmem.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/9958957cfa71505a-check.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/9958957cfa71505a-crc32_fast.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/9958957cfa71505a-crc64_fast.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/9958957cfa71505a-sha256.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-alone_decoder.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-alone_encoder.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-auto_decoder.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-block_buffer_decoder.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-block_buffer_encoder.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-block_decoder.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-block_encoder.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-block_header_decoder.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-block_header_encoder.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-block_util.o /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/f44dda72c9a620b7-common.o ...\n33.293  rustc            393872 391442   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\" -C metadata=9cf788c8acaa5824 ...\n33.308  aarch64-linux-g  393867 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n33.312  as               393877 393747   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.316  cc1              393878 393867   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n33.319  aarch64-linux-g  393880 391596   0 /usr/bin/aarch64-linux-gnu-ar s /target/aarch64-unknown-linux-gnu/debug/build/liblzma-sys-7a282dc632c937cc/out/liblzma.a\n33.321  as               393882 393433   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.325  as               393883 393751   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.329  aarch64-linux-g  393879 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n33.342  cc1              393885 393879   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n33.365  rustc            393892 389621   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name liblzma_sys --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"bindgen\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n33.368  as               393893 392290   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x509_lu.o /tmp/ccBdktFl.s\n33.373  as               393895 393393   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I xz/src/liblzma/api -I xz/src/liblzma/lzma -I xz/src/liblzma/lz -I xz/src/liblzma/check -I xz/src/liblzma/simple -I xz/src/liblzma/delta -I xz/src/liblzma/common -I xz/src/liblzma/rangecoder -I xz/src/common -I ...\n33.386  riscv64-linux-g  393901 392425   0 /usr/bin/riscv64-linux-gnu-ar cq /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/liblzma.a /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/0b27bbdc3d149821-tuklib_cpucores.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/0b27bbdc3d149821-tuklib_physmem.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/9958957cfa71505a-check.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/9958957cfa71505a-crc32_fast.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/9958957cfa71505a-crc64_fast.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/9958957cfa71505a-sha256.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-alone_decoder.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-alone_encoder.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-auto_decoder.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-block_buffer_decoder.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-block_buffer_encoder.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-block_decoder.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-block_encoder.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-block_header_decoder.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-block_header_encoder.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-block_util.o /target/riscv64gc-unknown-linux-gnu/debug/build/liblzma-sys-93e0896945a402bf/out/f44dda72c9a620b7-common.o ...\n33.400  build-script-bu  393897 391145   0 /target/debug/build/lock_api-2503a189a9387e15/build-script-build\n33.410  as               393902 392995   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x509name.o /tmp/ccYFe8UF.s\n33.415  rustc            393903 393897   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n33.427  as               393905 392934   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ebcd52e9457b6221-x509_vpm.o /tmp/ccbuS902.s\n"
    },
    {
      "argv": [
        "/target/debug/build/ash-18b97227eb4289a8/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 381125,
      "build_script_target_dir": "ash-18b97227eb4289a8",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/ash-18b97227eb4289a8/build-script-build",
      "pid": 381125,
      "ppid": 380958,
      "root_cargo_pid": 380958,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "ash",
      "cwd": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
      "event_id": "bsrun:6c83fa2429188748:f1d2e4686d87d918:2a08caf2034bc188",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/ash-18b97227eb4289a8/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
      "out_dir": "/target/debug/build/ash-18b97227eb4289a8/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
      "success": true,
      "target": null,
      "version": "0.38.0+1.3.281",
      "_owner": {
        "crate": "ash",
        "version": "0.38.0+1.3.281",
        "package_id": "path+file:///tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281#ash@0.38.0+1.3.281",
        "manifest_dir": "/tmp/crate-build-riscv64-s0buglg5/src/ash-0.38.0+1.3.281",
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
