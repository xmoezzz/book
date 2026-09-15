# `nextest-workspace-hack` `0.1.0`

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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
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
  "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
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
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-658104-1783995200841480395.map",
  "pid": 658104,
  "ppid": 658049,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-658104-1783995200841480395.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
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
  "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "workspace_root": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0"
  ],
  "packages": [
    {
      "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
      "name": "nextest-workspace-hack",
      "version": "0.1.0",
      "manifest_path": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0"
    }
  ],
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 658104,
  "ppid": 658049,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "nextest-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "event_id": "used:cc:83eb66d4b0e85bca:1bdce55565dfb0d4:5a9a44ca5b0349e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
  "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
  "pid": 658104,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "nextest-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "event_id": "used:cc:83eb66d4b0e85bca:7209ba89d9382698:5a9a44ca5b0349e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
  "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
  "pid": 658104,
  "sha256": "7bfe995c41a92a98e45a647b070d3807c02d9e3f1ea1fa5fbe9782f0a0ff0960",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "nextest-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "event_id": "used:cc:83eb66d4b0e85bca:68bb55a728bf8446:5a9a44ca5b0349e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
  "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
  "pid": 658104,
  "sha256": "1083a375eee179b966a09ab0a56a2c283eb032fbacc8c0f0cde16b29fbfc4bef",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "nextest-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "event_id": "used:cc:83eb66d4b0e85bca:bf9ef67f8c0de883:5a9a44ca5b0349e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
  "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
  "pid": 658104,
  "sha256": "6f3cfea01c4315c8f7166a3f0584e8ccfca8487af25e4872bd99f11043146781",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "nextest-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "event_id": "used:cc:83eb66d4b0e85bca:19ac3c35e0346f07:5a9a44ca5b0349e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
  "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
  "pid": 658104,
  "sha256": "94ed6ea030ee67470e6368368b77a9da2e682923eaa46c446905493372b123e4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "nextest-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "event_id": "used:cc:83eb66d4b0e85bca:5344d9f93744bde9:5a9a44ca5b0349e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
  "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
  "pid": 658104,
  "sha256": "33e2699dcf31eac23ec7c8c198ebfc204e342e569760b04519439d837738b1ce",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "nextest-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "event_id": "used:cc:83eb66d4b0e85bca:1b1366a9a6680ded:5a9a44ca5b0349e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
  "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
  "pid": 658104,
  "sha256": "275b2c1bb701c27d64e032fe033132eaa178d54a7b50cedf52c875e279f6c4cb",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
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
  "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "cargo_pkg_name": "nextest-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "context_path": "/tmp/native-trace-654008-1783995164359/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-654008-1783995164359/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 658104,
  "ppid": 658049,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
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
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-658104-1783995200841480395.map",
  "pid": 658104,
  "ppid": 658049,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-658104-1783995200841480395.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
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
  "parsed_event_count": 741,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 743,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "nown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n14.150  grep             659198 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n14.178  cat              659199 649576   0 /usr/bin/cat conftest.er1\n14.283  collect2         659210 659197   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2yikpA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n14.378  sed              659212 649576   0 \n14.378  rust-lld         659211 659210   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2yikpA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n14.378  ld.lld           659211 659210   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2yikpA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0 ...\n14.378  mv               659209 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n14.381  rm               659214 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n14.384  rm               659215 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n14.389  cat              659216 649576   0 /usr/bin/cat confdefs.h -\n14.395  rm               659217 649576   0 /usr/bin/rm -f conftest.o\n14.397  cc               659220 659219   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n14.401  cc               659221 659220   0 \n14.403  cc1              659222 659221   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n14.416  grep             659223 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n14.419  cat              659225 649576   0 /usr/bin/cat conftest.er1\n14.422  mv               659226 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n14.427  sed              659227 649576   0 /usr/bin/sed s/^/| / conftest.c\n14.431  cat              659228 649576   0 /usr/bin/cat confdefs.h -\n14.433  rm               659229 649576   0 /usr/bin/rm -f conftest.o\n14.436  cc               659231 659230   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n14.437  cc               659232 659231   0 /usr/bin/cc -c -fPIC conftest.c\n14.439  cc1              659233 659232   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n14.564  grep             659238 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n14.566  cat              659239 649576   0 /usr/bin/cat conftest.er1\n14.568  mv               659240 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n14.572  sed              659241 649576   0 /usr/bin/sed s/^/| / conftest.c\n14.583  rm               659243 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n14.637  rm               659244 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n14.637  cat              659263 649576   0 /usr/bin/cat confdefs.h -\n14.663  cc               659267 659266   0 \n14.664  rm               659264 649576   0 /usr/bin/rm -f conftest.o\n14.664  cc               659266 659265   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n14.713  cc1              659268 659267   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n14.764  cc1plus          659271 659269   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n14.765  riscv64-linux-g  659269 629151   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out ...\n14.827  as               659273 656695   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/f7deeeb1a9f9c241-memory-utils.o /tmp/ccJQNDOq.s\n14.860  powerpc64le-lin  659275 626080   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections  -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/crate -I  -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out -I ...\n14.865  cc1plus          659277 659275   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/crate -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n15.011  as               659281 659267   0 /usr/bin/as --64 -o conftest.o /tmp/cc7p0tgW.s\n15.012  build-script-bu  659282 659116   0 /target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build-script-build\n15.017  rustc            659284 659116   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name nextest_workspace_hack --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=86d5f1cfc6125f3b ...\n15.061  rm               659289 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n15.068  cat              659290 649576   0 /usr/bin/cat\n15.072  cat              659291 649576   0 /usr/bin/cat confdefs.h -\n15.076  rm               659292 649576   0 /usr/bin/rm -f conftest.o\n15.087  cc               659294 659293   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n15.092  cc               659295 659294   0 /usr/bin/cc -c -fPIC conftest.c\n15.094  cc1              659296 659295   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n15.147  as               659297 626316   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d ...\n15.173  grep             659298 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n15.178  cat              659302 649576   0 /usr/bin/cat conftest.er1\n15.191  mv               659303 649576   0 \n15.195  sed              659305 649576   0 /usr/bin/sed s/^/| / conftest.c\n15.200  cat              659306 649576   0 /usr/bin/cat confdefs.h -\n15.202  rm               659307 649576   0 /usr/bin/rm -f conftest.o\n15.209  as               659304 654146   0 \n15.212  cc               659310 659309   0 /usr/bin/cc -c -fPIC conftest.c\n15.212  cc               659309 659308   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n15.214  cc1              659311 659310   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n15.493  grep             659312 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n15.496  cat              659313 649576   0 /usr/bin/cat conftest.er1\n15.583  mv               659314 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n15.837  sed              659317 649576   0 /usr/bin/sed s/^/| / conftest.c\n15.843  rm               659318 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n15.846  rm               659319 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n15.849  cat              659320 649576   0 /usr/bin/cat confdefs.h -\n15.853  rm               659321 649576   0 /usr/bin/rm -f conftest.o\n15.867  cc1              659325 659324   0 \n15.867  cc               659323 659322   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n15.867  cc               659324 659323   0 \n15.899  as               659327 659324   0 /usr/bin/as --64 -o conftest.o /tmp/ccsZPYdM.s\n15.908  powerpc64le-lin  659328 629465   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -Wall ...\n15.908  rm               659329 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n15.913  cc1plus          659330 659328   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/ir/module-utils.cpp ...\n15.918  cat              659331 649576   0 /usr/bin/cat\n15.925  powerpc64le-lin  659332 629465   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -Wall ...\n15.929  cc1plus          659334 659332   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/ir/names.cpp ...\n15.929  powerpc64le-lin  659333 629465   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -Wall ...\n15.942  cc1plus          659335 659333   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/ir/possible-contents.cpp ...\n15.971  cat              659336 649576   0 /usr/bin/cat\n15.981  sed              659340 659339   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n15.988  cat              659341 649576   0 /usr/bin/cat confdefs.h -\n15.997  rm               659342 649576   0 /usr/bin/rm -f conftest.o conftest\n16.002  cc               659344 659343   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype\n16.005  cc               659345 659344   0 /usr/bin/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-659344-1783995213027497647.map\n16.007  cc1              659346 659345   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n16.066  as               659347 659345   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 --64 -o /tmp/cc4GPtR7.o /tmp/cceknH8T.s\n16.072  collect2         659348 659345   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccTA4slZ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n16.073  ld               659349 659348   0 /tmp/native-trace-643006-1783995068237/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccTA4slZ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n16.074  ld               659350 659349   0 /usr/bin/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccTA4slZ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n16.126  rustc            659355 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name yoke_derive --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yoke-derive-0.7.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n16.137  rustc            659358 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zerovec_derive --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerovec-derive-0.10.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n16.155  rustc            659356 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zerofrom_derive --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerofrom-derive-0.1.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n16.212  rustc            659366 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde_derive --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.219/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n16.254  cat              659368 649576   0 /usr/bin/cat conftest.err\n16.260  grep             659369 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n16.275  cat              659370 649576   0 /usr/bin/cat conftest.er1\n16.277  mv               659371 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n16.280  sed              659372 649576   0 /usr/bin/sed s/^/| / conftest.c\n16.283  rm               659373 649576   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n16.286  rm               659374 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n16.301  sed              659378 659377   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n16.375  rustc            659379 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_provider_macros --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_provider_macros-1.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n16.396  rustc            659367 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n16.408  aarch64-linux-g  659386 625892   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include ...\n16.408  rustc            659380 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prost_derive --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prost-derive-0.13.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n16.510  rustc            659359 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name displaydoc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/displaydoc-0.2.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"std\")) ...\n16.510  cat              659388 649576   0 \n16.510  cc1plus          659389 659386   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n16.510  rustc            659395 649548   0 \n16.511  rustc            659394 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name substrait_validator_derive --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/substrait-validator-derive-0.1.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n16.513  rm               659393 649576   0 /usr/bin/rm -f conftest.o conftest\n16.561  rustc            659396 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_derive --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-derive-0.4.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n16.563  cc               659398 659397   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype\n16.564  cc               659402 659398   0 /usr/bin/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-659398-1783995213587647059.map\n16.595  cc1              659405 659402   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n16.747  sh               659418 2147557   0 /bin/sh -c which ps\n16.778  which            659418 2147557   0 /usr/bin/which ps\n16.820  as               659423 659402   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 --64 -o /tmp/ccY4g4co.o /tmp/ccplNvl9.s\n16.875  ld               659430 659429   0 \n16.875  collect2         659428 659402   0 \n16.875  sh               659426 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.875  ps               659426 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.875  ld               659429 659428   0 /tmp/native-trace-643006-1783995068237/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMkT6GU.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n17.009  cat              659431 649576   0 /usr/bin/cat conftest.err\n17.085  grep             659432 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n17.088  cat              659433 649576   0 /usr/bin/cat conftest.er1\n17.090  mv               659434 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n17.148  sed              659435 649576   0 /usr/bin/sed s/^/| / conftest.c\n17.204  rm               659436 649576   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n17.262  rm               659437 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n17.307  sed              659441 659440   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n17.316  cat              659442 649576   0 /usr/bin/cat confdefs.h -\n17.316  rm               659443 649576   0 /usr/bin/rm -f conftest.o conftest\n17.326  sh               659444 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n17.329  cpuUsage.sh      659444 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n17.330  sed              659445 659444   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.363  cat              659446 659444   0 /usr/bin/cat /proc/2240539/stat\n17.397  cc               659448 659447   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype\n17.515  cc               659449 659448   0 /usr/bin/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-659448-1783995214420762789.map\n17.515  sleep            659451 659444   0 \n17.515  cat              659450 659444   0 /usr/bin/cat /proc/4193716/stat\n17.594  cc1              659452 659449   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n18.366  as               659453 659449   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 --64 -o /tmp/cc4ZP7ep.o /tmp/ccmHHJX4.s\n18.499  collect2         659454 659449   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLMv0Eu.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n18.555  sed              659455 659444   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.558  cat              659456 659444   0 /usr/bin/cat /proc/2240539/stat\n18.580  cat              659459 659444   0 /usr/bin/cat /proc/4193716/stat\n18.610  ld               659458 659454   0 /tmp/native-trace-643006-1783995068237/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLMv0Eu.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n18.611  ld               659461 659458   0 /usr/bin/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLMv0Eu.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n18.656  cat              659462 649576   0 /usr/bin/cat conftest.err\n18.695  grep             659463 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n18.696  cat              659464 649576   0 /usr/bin/cat conftest.er1\n18.732  mv               659465 649576   0 \n18.732  rm               659467 649576   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n18.732  rm               659468 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n18.732  sed              659466 649576   0 /usr/bin/sed s/^/| / conftest.c\n18.742  sed              659472 659471   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n18.810  cat              659473 649576   0 /usr/bin/cat confdefs.h -\n18.881  rm               659476 649576   0 /usr/bin/rm -f conftest.o conftest\n18.886  cc               659478 659477   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype\n18.891  cc               659479 659478   0 /usr/bin/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-659478-1783995215911290167.map\n18.895  cc1              659480 659479   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n18.916  as               659481 659479   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 --64 -o /tmp/ccarlyvc.o /tmp/ccDVoVyd.s\n18.924  ld               659483 659482   0 \n18.924  collect2         659482 659479   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfUh9Jo.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n18.925  ld               659484 659483   0 \n18.936  as               659485 647913   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/f7deeeb1a9f9c241-memory-utils.o /tmp/ccGWaI4j.s\n18.942  cat              659488 649576   0 /usr/bin/cat conftest.err\n18.942  grep             659489 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n18.947  cat              659490 649576   0 /usr/bin/cat conftest.er1\n18.952  mv               659491 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n18.957  sed              659492 649576   0 /usr/bin/sed s/^/| / conftest.c\n18.963  rm               659493 649576   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n18.967  rm               659494 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n18.979  sed              659498 659497   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n18.994  cat              659499 649576   0 /usr/bin/cat confdefs.h -\n18.998  rm               659500 649576   0 /usr/bin/rm -f conftest.o conftest\n19.008  cc               659503 659502   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype\n19.012  cc               659504 659503   0 /usr/bin/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-659503-1783995216030991234.map\n19.016  cc1              659505 659504   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n19.094  collect2         659507 659504   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccP8uiGE.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n19.094  as               659506 659504   0 \n19.127  ld               659508 659507   0 /tmp/native-trace-643006-1783995068237/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccP8uiGE.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n19.131  ld               659509 659508   0 \n19.298  cat              659510 649576   0 /usr/bin/cat conftest.err\n19.319  grep             659512 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n19.322  cat              659513 649576   0 /usr/bin/cat conftest.er1\n19.325  mv               659514 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n19.358  sed              659515 649576   0 /usr/bin/sed s/^/| / conftest.c\n19.387  rm               659516 649576   0 \n19.426  rm               659517 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n19.537  runc             659518 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process3647824218 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n19.905  sed              659530 659527   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n19.994  cat              659532 649576   0 /usr/bin/cat confdefs.h -\n20.060  rm               659536 649576   0 /usr/bin/rm -f conftest.o conftest\n20.063  cc               659538 659537   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype\n20.065  cc               659539 659538   0 /usr/bin/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-659538-1783995217086555384.map\n20.068  cc1              659540 659539   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n20.110  as               659541 659539   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 --64 -o /tmp/ccC0h7fx.o /tmp/ccMFsa47.s\n20.127  exe              659535 659518   0 /proc/self/exe init\n20.265  collect2         659552 659539   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc5CZZNT.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n20.267  ld               659553 659552   0 \n20.299  ld               659554 659553   0 /usr/bin/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc5CZZNT.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n20.353  cat              659556 649576   0 /usr/bin/cat conftest.err\n20.356  grep             659557 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n20.360  cat              659558 649576   0 /usr/bin/cat conftest.er1\n20.362  mv               659559 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n20.365  etcdctl          659543 659518   0 /usr/local/bin/etcdctl endpoint health\n20.369  sed              659560 649576   0 /usr/bin/sed s/^/| / conftest.c\n20.417  rm               659561 649576   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.421  rm               659562 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.477  cat              659564 649576   0 /usr/bin/cat confdefs.h -\n20.480  rm               659565 649576   0 /usr/bin/rm -f conftest.o\n20.521  cc               659567 659566   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c\n20.561  cc               659569 659567   0 /usr/bin/cc -c -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c\n20.562  cc1              659570 659569   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n20.700  cc               659575 659394   0 /tmp/native-trace-647230-1783995108983/shims/cc -Wl,--version-script=/target/debug/deps/rustcEqeUbh/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcEqeUbh/symbols.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.0.rcgu.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.1.rcgu.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.2.rcgu.o /target/debug/deps/rustcEqeUbh/rmeta.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.2a70930xd5ihj1m6gpj43rkxs.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib /target/debug/deps/libunicode_ident-71134888432ae9cf.rlib /target/debug/deps/libheck-68b0ff9b9f8bcb25.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n20.701  cc               659576 659575   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcEqeUbh/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcEqeUbh/symbols.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.0.rcgu.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.1.rcgu.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.2.rcgu.o /target/debug/deps/rustcEqeUbh/rmeta.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.2a70930xd5ihj1m6gpj43rkxs.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib /target/debug/deps/libunicode_ident-71134888432ae9cf.rlib /target/debug/deps/libheck-68b0ff9b9f8bcb25.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n20.814  rustc            659584 649548   0 \n20.846  rustc            659587 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fancy_regex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fancy-regex-0.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"perf\" --cfg feature=\"std\" ...\n20.875  cc               659581 659379   0 /tmp/native-trace-647230-1783995108983/shims/cc -Wl,--version-script=/target/debug/deps/rustcOF3H9V/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcOF3H9V/symbols.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.0.rcgu.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.1.rcgu.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.2.rcgu.o /target/debug/deps/rustcOF3H9V/rmeta.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.e6qi66xipcqji4ken8cee50uh.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib /target/debug/deps/libunicode_ident-71134888432ae9cf.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n20.905  collect2         659588 659576   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXgaq7c.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libsubstrait_validator_derive-c6881f41d39a1361.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcEqeUbh/raw-dylibs ...\n20.920  cc               659589 659581   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcOF3H9V/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcOF3H9V/symbols.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.0.rcgu.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.1.rcgu.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.2.rcgu.o /target/debug/deps/rustcOF3H9V/rmeta.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.e6qi66xipcqji4ken8cee50uh.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib /target/debug/deps/libunicode_ident-71134888432ae9cf.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n21.016  collect2         659592 659589   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoWkLVe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libicu_provider_macros-c2c067d0314674b7.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcOF3H9V/raw-dylibs ...\n21.016  ld.lld           659590 659588   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXgaq7c.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libsubstrait_validator_derive-c6881f41d39a1361.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcEqeUbh/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n21.052  ld.lld           659593 659592   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoWkLVe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libicu_provider_macros-c2c067d0314674b7.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcOF3H9V/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n21.117  rust-lld         659590 659588   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXgaq7c.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libsubstrait_validator_derive-c6881f41d39a1361.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n21.120  rust-lld         659593 659592   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoWkLVe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libicu_provider_macros-c2c067d0314674b7.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n21.354  as               659609 659569   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 --64 -o conftest.o /tmp/ccD48DNC.s\n21.419  grep             659610 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n21.423  cat              659611 649576   0 /usr/bin/cat conftest.er1\n21.426  mv               659612 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n21.431  rm               659613 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n21.435  cat              659614 649576   0 /usr/bin/cat\n21.443  cat              659615 649576   0 /usr/bin/cat confdefs.h -\n21.446  rm               659616 649576   0 /usr/bin/rm -f conftest.o\n21.454  cc               659618 659617   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include conftest.c\n21.454  cc               659619 659618   0 /usr/bin/cc -c -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include conftest.c\n21.458  cc1              659620 659619   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n21.888  riscv64-linux-g  659624 626155   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n22.039  cc1plus          659625 659624   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n22.053  sh               659623 2147557   0 /bin/sh -c which ps\n22.133  which            659623 2147557   0 /usr/bin/which ps\n22.191  sh               659627 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n22.285  ps               659627 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n22.500  as               659657 659619   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include --64 -o conftest.o /tmp/ccZRrzcv.s\n22.546  rm               659669 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n22.550  cat              659670 649576   0 /usr/bin/cat confdefs.h -\n22.625  cc               659672 659671   0 /tmp/native-trace-643006-1783995068237/shims/cc -E -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include conftest.c\n22.628  cc               659673 659672   0 /usr/bin/cc -E -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include conftest.c\n22.722  cc1              659674 659673   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -E -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include -imultiarch x86_64-linux-gnu conftest.c -mtune=generic -march=x86-64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -dumpbase conftest.c -dumpbase-ext .c ...\n22.832  rm               659676 649576   0 /usr/bin/rm -f conftest.err conftest.i conftest.c\n22.913  cat              659677 649576   0 /usr/bin/cat confdefs.h -\n22.976  rm               659679 649576   0 /usr/bin/rm -f conftest.o conftest\n22.980  cc               659681 659680   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/lib -lexpat\n23.006  aarch64-linux-g  659683 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n23.014  cc1plus          659684 659683   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/ir/type-updating.cpp ...\n23.036  as               659686 651979   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d ...\n23.073  rustc            659691 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.11.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"perf\" --cfg feature=\"perf-backtrack\" ...\n23.080  sh               659693 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n23.082  cc               659682 659681   0   conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include  -L/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/lib  -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-659681-1783995220005074668.map\n23.082  cpuUsage.sh      659693 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n23.086  sed              659694 659693   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n23.086  rustc            659692 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fancy_regex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fancy-regex-0.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"perf\" --cfg feature=\"std\" ...\n23.088  cc1              659695 659682   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n23.090  cat              659696 659693   0 /usr/bin/cat /proc/2240539/stat\n23.094  cat              659697 659693   0 /usr/bin/cat /proc/4193716/stat\n23.095  sleep            659699 659693   0 /usr/bin/sleep 1\n"
}
```

#### Record 15

```json
{
  "argv": [
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 658268,
  "build_script_target_dir": "nextest-workspace-hack-6f004b1889039ee0",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build-script-build",
  "pid": 658268,
  "ppid": 657991,
  "root_cargo_pid": 657991,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "_build_script_out_dir": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/out"
}
```

#### Record 16

```json
{
  "crate": "nextest-workspace-hack",
  "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "event_id": "bsrun:6b3569c1f92d1069:e19ba20bdaa1db6c:87f55097ebf11c6d",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
  "out_dir": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
  "success": true,
  "target": null,
  "version": "0.1.0",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
    "source": "cwd_prefix"
  }
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T02:13:42.093784+00:00",
  "crate": "nextest-workspace-hack",
  "version": "0.1.0",
  "architecture": "riscv64",
  "duration_seconds": 68.07278479868546,
  "trace_record_count": 16,
  "trace_owner_summary": {
    "owner_package_count": 1,
    "owner_packages": [
      {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
        "manifest_path": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0/Cargo.toml"
      }
    ],
    "attributed_event_count": 13,
    "unattributed_event_count": 3,
    "owners": [
      {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
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
      "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
      "workspace_root": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0"
      ],
      "packages": [
        {
          "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
          "name": "nextest-workspace-hack",
          "version": "0.1.0",
          "manifest_path": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0"
        }
      ],
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 658104,
      "ppid": 658049,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "nextest-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
      "event_id": "used:cc:83eb66d4b0e85bca:1bdce55565dfb0d4:5a9a44ca5b0349e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
      "pid": 658104,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "nextest-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
      "event_id": "used:cc:83eb66d4b0e85bca:7209ba89d9382698:5a9a44ca5b0349e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
      "pid": 658104,
      "sha256": "7bfe995c41a92a98e45a647b070d3807c02d9e3f1ea1fa5fbe9782f0a0ff0960",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "nextest-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
      "event_id": "used:cc:83eb66d4b0e85bca:68bb55a728bf8446:5a9a44ca5b0349e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
      "pid": 658104,
      "sha256": "1083a375eee179b966a09ab0a56a2c283eb032fbacc8c0f0cde16b29fbfc4bef",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "nextest-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
      "event_id": "used:cc:83eb66d4b0e85bca:bf9ef67f8c0de883:5a9a44ca5b0349e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
      "pid": 658104,
      "sha256": "6f3cfea01c4315c8f7166a3f0584e8ccfca8487af25e4872bd99f11043146781",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "nextest-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
      "event_id": "used:cc:83eb66d4b0e85bca:19ac3c35e0346f07:5a9a44ca5b0349e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
      "pid": 658104,
      "sha256": "94ed6ea030ee67470e6368368b77a9da2e682923eaa46c446905493372b123e4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "nextest-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
      "event_id": "used:cc:83eb66d4b0e85bca:5344d9f93744bde9:5a9a44ca5b0349e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
      "pid": 658104,
      "sha256": "33e2699dcf31eac23ec7c8c198ebfc204e342e569760b04519439d837738b1ce",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "nextest-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
      "event_id": "used:cc:83eb66d4b0e85bca:1b1366a9a6680ded:5a9a44ca5b0349e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
      "pid": 658104,
      "sha256": "275b2c1bb701c27d64e032fe033132eaa178d54a7b50cedf52c875e279f6c4cb",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
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
      "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
      "cargo_pkg_name": "nextest-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "context_path": "/tmp/native-trace-654008-1783995164359/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-654008-1783995164359/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 658104,
      "ppid": 658049,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
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
          "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8",
          "kind": "object",
          "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcDzUje8/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
          "kind": "object",
          "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.0qqq5zz.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
          "kind": "object",
          "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.0qqq5zz.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
          "kind": "object",
          "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.0qqq5zz.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
          "kind": "object",
          "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.0qqq5zz.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
          "kind": "object",
          "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.0qqq5zz.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
          "kind": "object",
          "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.0qqq5zz.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-658104-1783995200841480395.map",
      "pid": 658104,
      "ppid": 658049,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-658104-1783995200841480395.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
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
      "parsed_event_count": 741,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 743,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "nown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n14.150  grep             659198 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n14.178  cat              659199 649576   0 /usr/bin/cat conftest.er1\n14.283  collect2         659210 659197   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2yikpA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n14.378  sed              659212 649576   0 \n14.378  rust-lld         659211 659210   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2yikpA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n14.378  ld.lld           659211 659210   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2yikpA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0 ...\n14.378  mv               659209 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n14.381  rm               659214 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n14.384  rm               659215 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n14.389  cat              659216 649576   0 /usr/bin/cat confdefs.h -\n14.395  rm               659217 649576   0 /usr/bin/rm -f conftest.o\n14.397  cc               659220 659219   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n14.401  cc               659221 659220   0 \n14.403  cc1              659222 659221   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n14.416  grep             659223 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n14.419  cat              659225 649576   0 /usr/bin/cat conftest.er1\n14.422  mv               659226 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n14.427  sed              659227 649576   0 /usr/bin/sed s/^/| / conftest.c\n14.431  cat              659228 649576   0 /usr/bin/cat confdefs.h -\n14.433  rm               659229 649576   0 /usr/bin/rm -f conftest.o\n14.436  cc               659231 659230   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n14.437  cc               659232 659231   0 /usr/bin/cc -c -fPIC conftest.c\n14.439  cc1              659233 659232   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n14.564  grep             659238 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n14.566  cat              659239 649576   0 /usr/bin/cat conftest.er1\n14.568  mv               659240 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n14.572  sed              659241 649576   0 /usr/bin/sed s/^/| / conftest.c\n14.583  rm               659243 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n14.637  rm               659244 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n14.637  cat              659263 649576   0 /usr/bin/cat confdefs.h -\n14.663  cc               659267 659266   0 \n14.664  rm               659264 649576   0 /usr/bin/rm -f conftest.o\n14.664  cc               659266 659265   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n14.713  cc1              659268 659267   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n14.764  cc1plus          659271 659269   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n14.765  riscv64-linux-g  659269 629151   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out ...\n14.827  as               659273 656695   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/f7deeeb1a9f9c241-memory-utils.o /tmp/ccJQNDOq.s\n14.860  powerpc64le-lin  659275 626080   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections  -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/crate -I  -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out -I ...\n14.865  cc1plus          659277 659275   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out/cxxbridge/crate -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-14bfbaf436d2a7f7/out -I /tmp/crate-build-ppc64le-y5_hrrvu/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n15.011  as               659281 659267   0 /usr/bin/as --64 -o conftest.o /tmp/cc7p0tgW.s\n15.012  build-script-bu  659282 659116   0 /target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build-script-build\n15.017  rustc            659284 659116   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name nextest_workspace_hack --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=86d5f1cfc6125f3b ...\n15.061  rm               659289 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n15.068  cat              659290 649576   0 /usr/bin/cat\n15.072  cat              659291 649576   0 /usr/bin/cat confdefs.h -\n15.076  rm               659292 649576   0 /usr/bin/rm -f conftest.o\n15.087  cc               659294 659293   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n15.092  cc               659295 659294   0 /usr/bin/cc -c -fPIC conftest.c\n15.094  cc1              659296 659295   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n15.147  as               659297 626316   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d ...\n15.173  grep             659298 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n15.178  cat              659302 649576   0 /usr/bin/cat conftest.er1\n15.191  mv               659303 649576   0 \n15.195  sed              659305 649576   0 /usr/bin/sed s/^/| / conftest.c\n15.200  cat              659306 649576   0 /usr/bin/cat confdefs.h -\n15.202  rm               659307 649576   0 /usr/bin/rm -f conftest.o\n15.209  as               659304 654146   0 \n15.212  cc               659310 659309   0 /usr/bin/cc -c -fPIC conftest.c\n15.212  cc               659309 659308   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n15.214  cc1              659311 659310   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n15.493  grep             659312 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n15.496  cat              659313 649576   0 /usr/bin/cat conftest.er1\n15.583  mv               659314 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n15.837  sed              659317 649576   0 /usr/bin/sed s/^/| / conftest.c\n15.843  rm               659318 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n15.846  rm               659319 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n15.849  cat              659320 649576   0 /usr/bin/cat confdefs.h -\n15.853  rm               659321 649576   0 /usr/bin/rm -f conftest.o\n15.867  cc1              659325 659324   0 \n15.867  cc               659323 659322   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n15.867  cc               659324 659323   0 \n15.899  as               659327 659324   0 /usr/bin/as --64 -o conftest.o /tmp/ccsZPYdM.s\n15.908  powerpc64le-lin  659328 629465   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -Wall ...\n15.908  rm               659329 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n15.913  cc1plus          659330 659328   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/ir/module-utils.cpp ...\n15.918  cat              659331 649576   0 /usr/bin/cat\n15.925  powerpc64le-lin  659332 629465   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -Wall ...\n15.929  cc1plus          659334 659332   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/ir/names.cpp ...\n15.929  powerpc64le-lin  659333 629465   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -Wall ...\n15.942  cc1plus          659335 659333   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/ir/possible-contents.cpp ...\n15.971  cat              659336 649576   0 /usr/bin/cat\n15.981  sed              659340 659339   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n15.988  cat              659341 649576   0 /usr/bin/cat confdefs.h -\n15.997  rm               659342 649576   0 /usr/bin/rm -f conftest.o conftest\n16.002  cc               659344 659343   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype\n16.005  cc               659345 659344   0 /usr/bin/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-659344-1783995213027497647.map\n16.007  cc1              659346 659345   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n16.066  as               659347 659345   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 --64 -o /tmp/cc4GPtR7.o /tmp/cceknH8T.s\n16.072  collect2         659348 659345   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccTA4slZ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n16.073  ld               659349 659348   0 /tmp/native-trace-643006-1783995068237/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccTA4slZ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n16.074  ld               659350 659349   0 /usr/bin/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccTA4slZ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n16.126  rustc            659355 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name yoke_derive --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yoke-derive-0.7.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n16.137  rustc            659358 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zerovec_derive --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerovec-derive-0.10.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n16.155  rustc            659356 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zerofrom_derive --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerofrom-derive-0.1.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n16.212  rustc            659366 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde_derive --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.219/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n16.254  cat              659368 649576   0 /usr/bin/cat conftest.err\n16.260  grep             659369 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n16.275  cat              659370 649576   0 /usr/bin/cat conftest.er1\n16.277  mv               659371 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n16.280  sed              659372 649576   0 /usr/bin/sed s/^/| / conftest.c\n16.283  rm               659373 649576   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n16.286  rm               659374 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n16.301  sed              659378 659377   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n16.375  rustc            659379 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_provider_macros --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_provider_macros-1.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n16.396  rustc            659367 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n16.408  aarch64-linux-g  659386 625892   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include ...\n16.408  rustc            659380 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prost_derive --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prost-derive-0.13.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n16.510  rustc            659359 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name displaydoc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/displaydoc-0.2.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"std\")) ...\n16.510  cat              659388 649576   0 \n16.510  cc1plus          659389 659386   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n16.510  rustc            659395 649548   0 \n16.511  rustc            659394 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name substrait_validator_derive --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/substrait-validator-derive-0.1.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n16.513  rm               659393 649576   0 /usr/bin/rm -f conftest.o conftest\n16.561  rustc            659396 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_derive --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-derive-0.4.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n16.563  cc               659398 659397   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype\n16.564  cc               659402 659398   0 /usr/bin/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-659398-1783995213587647059.map\n16.595  cc1              659405 659402   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n16.747  sh               659418 2147557   0 /bin/sh -c which ps\n16.778  which            659418 2147557   0 /usr/bin/which ps\n16.820  as               659423 659402   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 --64 -o /tmp/ccY4g4co.o /tmp/ccplNvl9.s\n16.875  ld               659430 659429   0 \n16.875  collect2         659428 659402   0 \n16.875  sh               659426 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.875  ps               659426 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.875  ld               659429 659428   0 /tmp/native-trace-643006-1783995068237/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMkT6GU.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n17.009  cat              659431 649576   0 /usr/bin/cat conftest.err\n17.085  grep             659432 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n17.088  cat              659433 649576   0 /usr/bin/cat conftest.er1\n17.090  mv               659434 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n17.148  sed              659435 649576   0 /usr/bin/sed s/^/| / conftest.c\n17.204  rm               659436 649576   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n17.262  rm               659437 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n17.307  sed              659441 659440   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n17.316  cat              659442 649576   0 /usr/bin/cat confdefs.h -\n17.316  rm               659443 649576   0 /usr/bin/rm -f conftest.o conftest\n17.326  sh               659444 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n17.329  cpuUsage.sh      659444 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n17.330  sed              659445 659444   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.363  cat              659446 659444   0 /usr/bin/cat /proc/2240539/stat\n17.397  cc               659448 659447   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype\n17.515  cc               659449 659448   0 /usr/bin/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-659448-1783995214420762789.map\n17.515  sleep            659451 659444   0 \n17.515  cat              659450 659444   0 /usr/bin/cat /proc/4193716/stat\n17.594  cc1              659452 659449   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n18.366  as               659453 659449   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 --64 -o /tmp/cc4ZP7ep.o /tmp/ccmHHJX4.s\n18.499  collect2         659454 659449   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLMv0Eu.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n18.555  sed              659455 659444   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.558  cat              659456 659444   0 /usr/bin/cat /proc/2240539/stat\n18.580  cat              659459 659444   0 /usr/bin/cat /proc/4193716/stat\n18.610  ld               659458 659454   0 /tmp/native-trace-643006-1783995068237/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLMv0Eu.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n18.611  ld               659461 659458   0 /usr/bin/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLMv0Eu.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n18.656  cat              659462 649576   0 /usr/bin/cat conftest.err\n18.695  grep             659463 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n18.696  cat              659464 649576   0 /usr/bin/cat conftest.er1\n18.732  mv               659465 649576   0 \n18.732  rm               659467 649576   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n18.732  rm               659468 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n18.732  sed              659466 649576   0 /usr/bin/sed s/^/| / conftest.c\n18.742  sed              659472 659471   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n18.810  cat              659473 649576   0 /usr/bin/cat confdefs.h -\n18.881  rm               659476 649576   0 /usr/bin/rm -f conftest.o conftest\n18.886  cc               659478 659477   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype\n18.891  cc               659479 659478   0 /usr/bin/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-659478-1783995215911290167.map\n18.895  cc1              659480 659479   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n18.916  as               659481 659479   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 --64 -o /tmp/ccarlyvc.o /tmp/ccDVoVyd.s\n18.924  ld               659483 659482   0 \n18.924  collect2         659482 659479   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfUh9Jo.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n18.925  ld               659484 659483   0 \n18.936  as               659485 647913   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/f7deeeb1a9f9c241-memory-utils.o /tmp/ccGWaI4j.s\n18.942  cat              659488 649576   0 /usr/bin/cat conftest.err\n18.942  grep             659489 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n18.947  cat              659490 649576   0 /usr/bin/cat conftest.er1\n18.952  mv               659491 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n18.957  sed              659492 649576   0 /usr/bin/sed s/^/| / conftest.c\n18.963  rm               659493 649576   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n18.967  rm               659494 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n18.979  sed              659498 659497   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n18.994  cat              659499 649576   0 /usr/bin/cat confdefs.h -\n18.998  rm               659500 649576   0 /usr/bin/rm -f conftest.o conftest\n19.008  cc               659503 659502   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype\n19.012  cc               659504 659503   0 /usr/bin/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-659503-1783995216030991234.map\n19.016  cc1              659505 659504   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n19.094  collect2         659507 659504   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccP8uiGE.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n19.094  as               659506 659504   0 \n19.127  ld               659508 659507   0 /tmp/native-trace-643006-1783995068237/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccP8uiGE.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n19.131  ld               659509 659508   0 \n19.298  cat              659510 649576   0 /usr/bin/cat conftest.err\n19.319  grep             659512 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n19.322  cat              659513 649576   0 /usr/bin/cat conftest.er1\n19.325  mv               659514 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n19.358  sed              659515 649576   0 /usr/bin/sed s/^/| / conftest.c\n19.387  rm               659516 649576   0 \n19.426  rm               659517 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n19.537  runc             659518 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process3647824218 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n19.905  sed              659530 659527   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n19.994  cat              659532 649576   0 /usr/bin/cat confdefs.h -\n20.060  rm               659536 649576   0 /usr/bin/rm -f conftest.o conftest\n20.063  cc               659538 659537   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype\n20.065  cc               659539 659538   0 /usr/bin/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/lib -lfreetype -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-659538-1783995217086555384.map\n20.068  cc1              659540 659539   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n20.110  as               659541 659539   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 --64 -o /tmp/ccC0h7fx.o /tmp/ccMFsa47.s\n20.127  exe              659535 659518   0 /proc/self/exe init\n20.265  collect2         659552 659539   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc5CZZNT.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n20.267  ld               659553 659552   0 \n20.299  ld               659554 659553   0 /usr/bin/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc5CZZNT.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n20.353  cat              659556 649576   0 /usr/bin/cat conftest.err\n20.356  grep             659557 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n20.360  cat              659558 649576   0 /usr/bin/cat conftest.er1\n20.362  mv               659559 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n20.365  etcdctl          659543 659518   0 /usr/local/bin/etcdctl endpoint health\n20.369  sed              659560 649576   0 /usr/bin/sed s/^/| / conftest.c\n20.417  rm               659561 649576   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.421  rm               659562 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.477  cat              659564 649576   0 /usr/bin/cat confdefs.h -\n20.480  rm               659565 649576   0 /usr/bin/rm -f conftest.o\n20.521  cc               659567 659566   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c\n20.561  cc               659569 659567   0 /usr/bin/cc -c -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 conftest.c\n20.562  cc1              659570 659569   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n20.700  cc               659575 659394   0 /tmp/native-trace-647230-1783995108983/shims/cc -Wl,--version-script=/target/debug/deps/rustcEqeUbh/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcEqeUbh/symbols.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.0.rcgu.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.1.rcgu.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.2.rcgu.o /target/debug/deps/rustcEqeUbh/rmeta.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.2a70930xd5ihj1m6gpj43rkxs.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib /target/debug/deps/libunicode_ident-71134888432ae9cf.rlib /target/debug/deps/libheck-68b0ff9b9f8bcb25.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n20.701  cc               659576 659575   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcEqeUbh/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcEqeUbh/symbols.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.0.rcgu.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.1.rcgu.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.2.rcgu.o /target/debug/deps/rustcEqeUbh/rmeta.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.2a70930xd5ihj1m6gpj43rkxs.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib /target/debug/deps/libunicode_ident-71134888432ae9cf.rlib /target/debug/deps/libheck-68b0ff9b9f8bcb25.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n20.814  rustc            659584 649548   0 \n20.846  rustc            659587 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fancy_regex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fancy-regex-0.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"perf\" --cfg feature=\"std\" ...\n20.875  cc               659581 659379   0 /tmp/native-trace-647230-1783995108983/shims/cc -Wl,--version-script=/target/debug/deps/rustcOF3H9V/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcOF3H9V/symbols.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.0.rcgu.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.1.rcgu.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.2.rcgu.o /target/debug/deps/rustcOF3H9V/rmeta.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.e6qi66xipcqji4ken8cee50uh.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib /target/debug/deps/libunicode_ident-71134888432ae9cf.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n20.905  collect2         659588 659576   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXgaq7c.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libsubstrait_validator_derive-c6881f41d39a1361.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcEqeUbh/raw-dylibs ...\n20.920  cc               659589 659581   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcOF3H9V/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcOF3H9V/symbols.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.0.rcgu.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.1.rcgu.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.2.rcgu.o /target/debug/deps/rustcOF3H9V/rmeta.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.e6qi66xipcqji4ken8cee50uh.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib /target/debug/deps/libunicode_ident-71134888432ae9cf.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n21.016  collect2         659592 659589   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoWkLVe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libicu_provider_macros-c2c067d0314674b7.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcOF3H9V/raw-dylibs ...\n21.016  ld.lld           659590 659588   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXgaq7c.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libsubstrait_validator_derive-c6881f41d39a1361.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcEqeUbh/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n21.052  ld.lld           659593 659592   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoWkLVe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libicu_provider_macros-c2c067d0314674b7.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcOF3H9V/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n21.117  rust-lld         659590 659588   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXgaq7c.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libsubstrait_validator_derive-c6881f41d39a1361.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n21.120  rust-lld         659593 659592   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoWkLVe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libicu_provider_macros-c2c067d0314674b7.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n21.354  as               659609 659569   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 --64 -o conftest.o /tmp/ccD48DNC.s\n21.419  grep             659610 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n21.423  cat              659611 649576   0 /usr/bin/cat conftest.er1\n21.426  mv               659612 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n21.431  rm               659613 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n21.435  cat              659614 649576   0 /usr/bin/cat\n21.443  cat              659615 649576   0 /usr/bin/cat confdefs.h -\n21.446  rm               659616 649576   0 /usr/bin/rm -f conftest.o\n21.454  cc               659618 659617   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include conftest.c\n21.454  cc               659619 659618   0 /usr/bin/cc -c -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include conftest.c\n21.458  cc1              659620 659619   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n21.888  riscv64-linux-g  659624 626155   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n22.039  cc1plus          659625 659624   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n22.053  sh               659623 2147557   0 /bin/sh -c which ps\n22.133  which            659623 2147557   0 /usr/bin/which ps\n22.191  sh               659627 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n22.285  ps               659627 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n22.500  as               659657 659619   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include --64 -o conftest.o /tmp/ccZRrzcv.s\n22.546  rm               659669 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n22.550  cat              659670 649576   0 /usr/bin/cat confdefs.h -\n22.625  cc               659672 659671   0 /tmp/native-trace-643006-1783995068237/shims/cc -E -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include conftest.c\n22.628  cc               659673 659672   0 /usr/bin/cc -E -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include conftest.c\n22.722  cc1              659674 659673   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -E -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include -imultiarch x86_64-linux-gnu conftest.c -mtune=generic -march=x86-64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -dumpbase conftest.c -dumpbase-ext .c ...\n22.832  rm               659676 649576   0 /usr/bin/rm -f conftest.err conftest.i conftest.c\n22.913  cat              659677 649576   0 /usr/bin/cat confdefs.h -\n22.976  rm               659679 649576   0 /usr/bin/rm -f conftest.o conftest\n22.980  cc               659681 659680   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/lib -lexpat\n23.006  aarch64-linux-g  659683 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n23.014  cc1plus          659684 659683   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/ir/type-updating.cpp ...\n23.036  as               659686 651979   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d ...\n23.073  rustc            659691 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.11.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"perf\" --cfg feature=\"perf-backtrack\" ...\n23.080  sh               659693 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n23.082  cc               659682 659681   0   conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include  -L/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/lib  -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-659681-1783995220005074668.map\n23.082  cpuUsage.sh      659693 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n23.086  sed              659694 659693   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n23.086  rustc            659692 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fancy_regex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fancy-regex-0.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"perf\" --cfg feature=\"std\" ...\n23.088  cc1              659695 659682   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n23.090  cat              659696 659693   0 /usr/bin/cat /proc/2240539/stat\n23.094  cat              659697 659693   0 /usr/bin/cat /proc/4193716/stat\n23.095  sleep            659699 659693   0 /usr/bin/sleep 1\n"
    },
    {
      "argv": [
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 658268,
      "build_script_target_dir": "nextest-workspace-hack-6f004b1889039ee0",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build-script-build",
      "pid": 658268,
      "ppid": 657991,
      "root_cargo_pid": 657991,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "nextest-workspace-hack",
      "cwd": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
      "event_id": "bsrun:6b3569c1f92d1069:e19ba20bdaa1db6c:87f55097ebf11c6d",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
      "out_dir": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
      "success": true,
      "target": null,
      "version": "0.1.0",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-bxn3gmx8/src/nextest-workspace-hack-0.1.0",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
  "item": {
    "rank": 2511,
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "crate_id": "683061",
    "version_id": "637337",
    "downloads": 4967084,
    "cumulative_downloads": 104774238593,
    "cumulative_share_of_global": 0.3917266903569677,
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
