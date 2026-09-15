# `ducc-sys` `0.1.2`

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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
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
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
    "/target/debug/deps",
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
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.00.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.02.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.03.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.01.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.04.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.05.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.06.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.07.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.08.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.09.rcgu.o",
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
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib(hashbrown-1448c95121de53aa.hashbrown.c0386ddbfadcbbc1-cgu.0.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-906917-1783998295538715164.map",
  "pid": 906917,
  "ppid": 906903,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-906917-1783998295538715164.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/libduktape.a`

Owner: `ducc-sys` `0.1.2`

### Source files

* `/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2/duktape/duktape.c`
* `/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2/duktape/wrapper.c`

### Source acquisition records

_None._

### Source preparation records

#### Record 1

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-fno-omit-frame-pointer",
    "-I",
    "duktape",
    "-Wall",
    "-Wextra",
    "-std=c99",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o",
    "-c",
    "duktape/duktape.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 906938,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 906939,
  "ppid": 906938,
  "root_cargo_pid": 906879,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 2

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-fno-omit-frame-pointer",
    "-I",
    "duktape",
    "-Wall",
    "-Wextra",
    "-std=c99",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o",
    "-c",
    "duktape/wrapper.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 906938,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 907006,
  "ppid": 906938,
  "root_cargo_pid": 906879,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

### Compilation records

#### Record 1

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "duktape",
    "-imultiarch",
    "aarch64-linux-gnu",
    "duktape/duktape.c",
    "-quiet",
    "-dumpbase",
    "duktape.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o",
    "-g",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c99",
    "-ffunction-sections",
    "..."
  ],
  "src": "duktape/duktape.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 906941,
  "ppid": 906939,
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "root_cargo_pid": 906879,
  "build_script_root_pid": 906938,
  "build_script_related": true,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 2

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "duktape",
    "-imultiarch",
    "aarch64-linux-gnu",
    "duktape/wrapper.c",
    "-quiet",
    "-dumpbase",
    "wrapper.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o",
    "-g",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c99",
    "-ffunction-sections",
    "..."
  ],
  "src": "duktape/wrapper.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 907008,
  "ppid": 907006,
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "root_cargo_pid": 906879,
  "build_script_root_pid": 906938,
  "build_script_related": true,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

### Archive records

#### Record 1

```json
{
  "event": "archive",
  "tool": "/usr/bin/aarch64-linux-gnu-ar",
  "real_tool": "/usr/bin/aarch64-linux-gnu-ar",
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "crs",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/libduktape.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o"
  ],
  "archive": "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/libduktape.a",
  "objects": [
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 907010,
  "ppid": 906938,
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "root_cargo_pid": 906879,
  "build_script_root_pid": 906938,
  "build_script_related": true,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

### Native link records

_None._

### Resolved link records

_None._

### Resolved native inputs

_None._

## Complete analysis record stream

These are the recovered/enriched/generated records actually supplied to native-flow reconstruction.

### Analysis records

#### Record 1

```json
{
  "event": "native_trace_root_context",
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "workspace_root": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.45",
      "name": "cc",
      "version": "1.0.45",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.45/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.45"
    },
    {
      "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
      "name": "ducc-sys",
      "version": "0.1.2",
      "manifest_path": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2"
    }
  ],
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 906917,
  "ppid": 906903,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ducc-sys",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "event_id": "used:cc:69651ebbf736a3c5:efc6dedd2e113e45:abb9a54dbbb5546d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
  "pid": 906917,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ducc-sys",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "event_id": "used:cc:69651ebbf736a3c5:571eca0f799bb996:abb9a54dbbb5546d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
  "pid": 906917,
  "sha256": "72352c7ef1391be36c01d56b8ad74f827acffbe217081620b49b9b34117e0d74",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ducc-sys",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "event_id": "used:cc:69651ebbf736a3c5:f1accbf6c33c0e98:abb9a54dbbb5546d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
  "pid": 906917,
  "sha256": "b59390c3d89c011bf2b38587f580fc0dca19387a9e2ce0702cead8dfa80694c6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ducc-sys",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "event_id": "used:cc:69651ebbf736a3c5:c0259dfdd845c058:abb9a54dbbb5546d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
  "pid": 906917,
  "sha256": "da0c7863ead8b43b590c8f2e62a7fb9798aff9ad6dc7d8e36dec059180a8c812",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ducc-sys",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "event_id": "used:cc:69651ebbf736a3c5:47061bd04730e4ec:abb9a54dbbb5546d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
  "pid": 906917,
  "sha256": "c949106b42124b2876edba770c88595e71a537199887e954c8bead3f8ba643c1",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ducc-sys",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "event_id": "used:cc:69651ebbf736a3c5:f694bb3809f31a43:abb9a54dbbb5546d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
  "pid": 906917,
  "sha256": "7f90412cf2ad6caa6bdc5e95b229fb00eaa8514d4fa5c12390d1aa09ea75ef3f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ducc-sys",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "event_id": "used:cc:69651ebbf736a3c5:0c3ab9a381145413:abb9a54dbbb5546d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
  "pid": 906917,
  "sha256": "8335479aab6d0505c484661a5ba388f20d3ec4110223dc32f606744e099fe03c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ducc-sys",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "event_id": "used:cc:69651ebbf736a3c5:59ea4e824b7aca79:abb9a54dbbb5546d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
  "pid": 906917,
  "sha256": "ae52d18772ff8aa7cec8b14f73b369280c72261717d71592b0db6378f0d8a596",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ducc-sys",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "event_id": "used:cc:69651ebbf736a3c5:81b425daf9c30482:abb9a54dbbb5546d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
  "pid": 906917,
  "sha256": "ebb840d8cd1c2450f9aeb6da8e1e2f6080f4f8c141b4290591e40882d407cc38",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ducc-sys",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "event_id": "used:cc:69651ebbf736a3c5:0893b53b667c2da4:abb9a54dbbb5546d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
  "pid": 906917,
  "sha256": "284d84f7f81d89ec89645b2a82d086f655ecc90a264df977b30b9207cf79cd39",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 13

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
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
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 14

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "cargo_pkg_name": "ducc-sys",
  "cargo_pkg_version": "0.1.2",
  "context_path": "/tmp/native-trace-906565-1783998293152/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-906565-1783998293152/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 906917,
  "ppid": 906903,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 15

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
    "/target/debug/deps",
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
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.00.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.02.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.03.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.01.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.04.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.05.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.06.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.07.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.08.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.09.rcgu.o",
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
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib(hashbrown-1448c95121de53aa.hashbrown.c0386ddbfadcbbc1-cgu.0.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-906917-1783998295538715164.map",
  "pid": 906917,
  "ppid": 906903,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-906917-1783998295538715164.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 16

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

#### Record 17

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 1,
  "parsed_event_count": 78,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 79,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "0.102   TIME(s) PCOMM            PID    PPID   RET ARGS\ncargo            906879 906565   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n0.114   rustc            906880 906879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n0.134   rustc            906886 906879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.45/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"num_cpus\", \"parallel\")) -C metadata=9e0bc4e1d16e6475 ...\n0.470   rustc            906903 906879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"bindgen\", \"build-ffi-gen\", \"use-exec-timeout-check\")) -C metadata=4b2b2b459039c355 ...\n0.507   cc               906917 906903   0 /tmp/native-trace-906565-1783998293152/shims/cc -m64 /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-5ab4653aa6383c98.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd ...\n0.507   cc               906918 906917   0 /usr/bin/cc -m64 /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-5ab4653aa6383c98.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd ...\n0.510   collect2         906919 906918   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccFLL6V3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.511   ld.lld           906920 906919   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccFLL6V3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0 ...\n0.512   rust-lld         906920 906919   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccFLL6V3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.561   build-script-bu  906938 906879   0 /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build-script-build\n0.563   aarch64-linux-g  906939 906938   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -I duktape -Wall -Wextra -std=c99 -o /target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o -c duktape/duktape.c\n0.564   cc1              906941 906939   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I duktape -imultiarch aarch64-linux-gnu duktape/duktape.c -quiet -dumpbase duktape.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o -g -O0 -Wall -Wextra -std=c99 -ffunction-sections ...\n0.857   cargo            906942 906802   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n0.869   rustc            906943 906942   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n0.889   rustc            906949 906942   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.45/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"num_cpus\", \"parallel\")) -C metadata=9e0bc4e1d16e6475 ...\n1.220   rustc            906966 906942   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"bindgen\", \"build-ffi-gen\", \"use-exec-timeout-check\")) -C metadata=4b2b2b459039c355 ...\n1.254   cc               906980 906966   0 /tmp/native-trace-906802-1783998293688/shims/cc -m64 /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustclk1esL/symbols.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0mpxqxh.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-5ab4653aa6383c98.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd ...\n1.255   cc               906981 906980   0 /usr/bin/cc -m64 /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustclk1esL/symbols.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0mpxqxh.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-5ab4653aa6383c98.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd ...\n1.257   collect2         906982 906981   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1nG5Va.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n1.258   ld.lld           906983 906982   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1nG5Va.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0 ...\n1.258   rust-lld         906983 906982   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1nG5Va.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n1.301   build-script-bu  907001 906942   0 /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build-script-build\n1.303   riscv64-linux-g  907002 907001   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -g -fno-omit-frame-pointer -march=rv64gc -mabi=lp64 -I duktape -Wall -Wextra -std=c99 -o /target/riscv64gc-unknown-linux-gnu/debug/build/ducc-sys-c5bedf43582ed6cc/out/duktape/duktape.o -c duktape/duktape.c\n1.304   cc1              907004 907002   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I duktape -imultilib . -imultiarch riscv64-linux-gnu duktape/duktape.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/ducc-sys-c5bedf43582ed6cc/out/duktape/ -dumpbase duktape.c -dumpbase-ext .c -march=rv64gc -mabi=lp64 -misa-spec=2.2 -march=rv64imafdc ...\n1.774   as               907005 906939   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I duktape -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o /tmp/ccEwwpWH.s\n1.998   aarch64-linux-g  907006 906938   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -I duktape -Wall -Wextra -std=c99 -o /target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o -c duktape/wrapper.c\n1.999   cc1              907008 907006   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I duktape -imultiarch aarch64-linux-gnu duktape/wrapper.c -quiet -dumpbase wrapper.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o -g -O0 -Wall -Wextra -std=c99 -ffunction-sections ...\n2.034   as               907009 907006   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I duktape -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o /tmp/cc70r4DI.s\n2.046   aarch64-linux-g  907010 906938   0 /usr/bin/aarch64-linux-gnu-ar crs /target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/libduktape.a /target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o /target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o\n2.054   rustc            907013 906879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ducc_sys --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"bindgen\", \"build-ffi-gen\", \"use-exec-timeout-check\")) -C metadata=f68ba6762b7286e5 ...\n5.779   runc             907021 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process1242725692 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n5.785   exe              907029 907021   0 /proc/self/exe init\n5.800   curl             907031 907021   0 /usr/bin/curl -f http://localhost:9091/healthz\n7.846   sh               907038 2147557   0 /bin/sh -c which ps\n7.847   which            907038 2147557   0 /usr/bin/which ps\n7.849   sh               907039 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n7.850   ps               907039 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n7.872   sh               907040 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n7.873   cpuUsage.sh      907040 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n7.874   sed              907041 907040   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n7.875   cat              907042 907040   0 /usr/bin/cat /proc/2240539/stat\n7.876   cat              907043 907040   0 /usr/bin/cat /proc/4193716/stat\n7.877   sleep            907044 907040   0 /usr/bin/sleep 1\n8.879   sed              907045 907040   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n8.882   cat              907046 907040   0 /usr/bin/cat /proc/2240539/stat\n8.885   cat              907048 907040   0 /usr/bin/cat /proc/4193716/stat\n9.369   16               907050 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n9.381   frpc             907050 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n12.849  sh               907056 2147557   0 /bin/sh -c which ps\n12.850  which            907056 2147557   0 /usr/bin/which ps\n12.853  sh               907057 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n12.854  ps               907057 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n12.884  sh               907058 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n12.885  cpuUsage.sh      907058 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n12.886  sed              907059 907058   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n12.889  cat              907060 907058   0 /usr/bin/cat /proc/2240539/stat\n12.890  cat              907061 907058   0 /usr/bin/cat /proc/4193716/stat\n12.891  sleep            907062 907058   0 /usr/bin/sleep 1\n13.894  sed              907063 907058   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n13.896  cat              907064 907058   0 /usr/bin/cat /proc/2240539/stat\n13.899  cat              907066 907058   0 /usr/bin/cat /proc/4193716/stat\n14.746  runc             907068 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process1305497709 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n14.752  exe              907075 907068   0 /proc/self/exe init\n14.785  curl             907078 907068   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n17.262  runc             907084 905159   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b37b484559c5e0a6efd41fe438558e681a2ec89c29eded851e201dffdac --log-format json --systemd-cgroup kill --all b37b484559c5e0a6efd41fe438558e681a2ec89c29eded851e201dffdacc59d7 9\n17.270  runc             907091 905159   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b37b484559c5e0a6efd41fe438558e681a2ec89c29eded851e201dffdac --log-format json --systemd-cgroup delete b37b484559c5e0a6efd41fe438558e681a2ec89c29eded851e201dffdacc59d7\n17.453  containerd-shim  907097 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id b37b484559c5e0a6efd41fe438558e681a2ec89c29eded851e201dffdacc59d7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b37b484559c5e0a6efd41fe438558e681a2ec89c29eded851e201dffdac delete\n17.456  runc             907104 907097   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b37b484559c5e0a6efd41fe438558e681a2ec89c29eded851e201dffdacc59d --log-format json delete --force b37b484559c5e0a6efd41fe438558e681a2ec89c29eded851e201dffdacc59d7\n17.501  sh               907112 907109   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth45c2496\n17.502  ethtool          907113 907112   0 /usr/sbin/ethtool -i veth45c2496\n17.502  sed              907114 907112   0 /usr/bin/sed -n s/^driver: //p\n17.509  systemd-sysctl   907117 907109   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth45c2496 --prefix=/net/ipv4/neigh/veth45c2496 --prefix=/net/ipv6/conf/veth45c2496 --prefix=/net/ipv6/neigh/veth45c2496\n18.362  runc             907119 906740   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/569e55617dec3b92ea9a4e2260a682a72353cf3ffeb9c98611815f89c84 --log-format json --systemd-cgroup kill --all 569e55617dec3b92ea9a4e2260a682a72353cf3ffeb9c98611815f89c847d45b 9\n18.381  runc             907125 906740   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/569e55617dec3b92ea9a4e2260a682a72353cf3ffeb9c98611815f89c84 --log-format json --systemd-cgroup delete 569e55617dec3b92ea9a4e2260a682a72353cf3ffeb9c98611815f89c847d45b\n18.577  containerd-shim  907131 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 569e55617dec3b92ea9a4e2260a682a72353cf3ffeb9c98611815f89c847d45b -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/569e55617dec3b92ea9a4e2260a682a72353cf3ffeb9c98611815f89c84 delete\n18.580  runc             907137 907131   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/569e55617dec3b92ea9a4e2260a682a72353cf3ffeb9c98611815f89c847d45 --log-format json delete --force 569e55617dec3b92ea9a4e2260a682a72353cf3ffeb9c98611815f89c847d45b\n18.617  systemd-sysctl   907143 907109   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb74b48e --prefix=/net/ipv4/neigh/vethb74b48e --prefix=/net/ipv6/conf/vethb74b48e --prefix=/net/ipv6/neigh/vethb74b48e\n18.659  rustup           907146 906576   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n"
}
```

#### Record 18

```json
{
  "argv": [
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 906938,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build-script-build",
  "pid": 906938,
  "ppid": 906879,
  "root_cargo_pid": 906879,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out"
}
```

#### Record 19

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-fno-omit-frame-pointer",
    "-I",
    "duktape",
    "-Wall",
    "-Wextra",
    "-std=c99",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o",
    "-c",
    "duktape/duktape.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 906938,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 906939,
  "ppid": 906938,
  "root_cargo_pid": 906879,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 20

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "duktape",
    "-imultiarch",
    "aarch64-linux-gnu",
    "duktape/duktape.c",
    "-quiet",
    "-dumpbase",
    "duktape.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o",
    "-g",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c99",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 906938,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 906941,
  "ppid": 906939,
  "root_cargo_pid": 906879,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 21

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-I",
    "duktape",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o",
    "/tmp/ccEwwpWH.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 906938,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 907005,
  "ppid": 906939,
  "root_cargo_pid": 906879,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 22

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-fno-omit-frame-pointer",
    "-I",
    "duktape",
    "-Wall",
    "-Wextra",
    "-std=c99",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o",
    "-c",
    "duktape/wrapper.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 906938,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 907006,
  "ppid": 906938,
  "root_cargo_pid": 906879,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 23

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "duktape",
    "-imultiarch",
    "aarch64-linux-gnu",
    "duktape/wrapper.c",
    "-quiet",
    "-dumpbase",
    "wrapper.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o",
    "-g",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c99",
    "-ffunction-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 906938,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 907008,
  "ppid": 907006,
  "root_cargo_pid": 906879,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 24

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-I",
    "duktape",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o",
    "/tmp/cc70r4DI.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 906938,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 907009,
  "ppid": 907006,
  "root_cargo_pid": 906879,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 25

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "crs",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/libduktape.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 906938,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 907010,
  "ppid": 906938,
  "root_cargo_pid": 906879,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 26

```json
{
  "crate": "ducc-sys",
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "event_id": "bsrun:91b8913f305db1e2:e9794bf2d1e8e296:c38049f959723422",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
  "success": true,
  "target": null,
  "version": "0.1.2",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  }
}
```

#### Record 27

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "duktape",
    "-imultiarch",
    "aarch64-linux-gnu",
    "duktape/duktape.c",
    "-quiet",
    "-dumpbase",
    "duktape.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o",
    "-g",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c99",
    "-ffunction-sections",
    "..."
  ],
  "src": "duktape/duktape.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 906941,
  "ppid": 906939,
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "root_cargo_pid": 906879,
  "build_script_root_pid": 906938,
  "build_script_related": true,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 28

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "duktape",
    "-imultiarch",
    "aarch64-linux-gnu",
    "duktape/wrapper.c",
    "-quiet",
    "-dumpbase",
    "wrapper.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o",
    "-g",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c99",
    "-ffunction-sections",
    "..."
  ],
  "src": "duktape/wrapper.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 907008,
  "ppid": 907006,
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "root_cargo_pid": 906879,
  "build_script_root_pid": 906938,
  "build_script_related": true,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 29

```json
{
  "event": "archive",
  "tool": "/usr/bin/aarch64-linux-gnu-ar",
  "real_tool": "/usr/bin/aarch64-linux-gnu-ar",
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "crs",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/libduktape.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o"
  ],
  "archive": "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/libduktape.a",
  "objects": [
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 907010,
  "ppid": 906938,
  "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "root_cargo_pid": 906879,
  "build_script_root_pid": 906938,
  "build_script_related": true,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T03:05:19.497619+00:00",
  "crate": "ducc-sys",
  "version": "0.1.2",
  "architecture": "aarch64",
  "duration_seconds": 31.024108913727105,
  "trace_record_count": 26,
  "trace_owner_summary": {
    "owner_package_count": 2,
    "owner_packages": [
      {
        "crate": "cc",
        "version": "1.0.45",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.45",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.45",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.45/Cargo.toml"
      },
      {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
        "manifest_path": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2/Cargo.toml"
      }
    ],
    "attributed_event_count": 16,
    "unattributed_event_count": 10,
    "owners": [
      {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "event_count": 16,
        "kind_counts": {
          "native_trace_root_context": 1,
          "exec": 1,
          "used_input": 10,
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
      "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "workspace_root": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.45",
          "name": "cc",
          "version": "1.0.45",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.45/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.45"
        },
        {
          "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
          "name": "ducc-sys",
          "version": "0.1.2",
          "manifest_path": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2"
        }
      ],
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 906917,
      "ppid": 906903,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ducc-sys",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "event_id": "used:cc:69651ebbf736a3c5:efc6dedd2e113e45:abb9a54dbbb5546d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
      "pid": 906917,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ducc-sys",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "event_id": "used:cc:69651ebbf736a3c5:571eca0f799bb996:abb9a54dbbb5546d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
      "pid": 906917,
      "sha256": "72352c7ef1391be36c01d56b8ad74f827acffbe217081620b49b9b34117e0d74",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ducc-sys",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "event_id": "used:cc:69651ebbf736a3c5:f1accbf6c33c0e98:abb9a54dbbb5546d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
      "pid": 906917,
      "sha256": "b59390c3d89c011bf2b38587f580fc0dca19387a9e2ce0702cead8dfa80694c6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ducc-sys",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "event_id": "used:cc:69651ebbf736a3c5:c0259dfdd845c058:abb9a54dbbb5546d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
      "pid": 906917,
      "sha256": "da0c7863ead8b43b590c8f2e62a7fb9798aff9ad6dc7d8e36dec059180a8c812",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ducc-sys",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "event_id": "used:cc:69651ebbf736a3c5:47061bd04730e4ec:abb9a54dbbb5546d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
      "pid": 906917,
      "sha256": "c949106b42124b2876edba770c88595e71a537199887e954c8bead3f8ba643c1",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ducc-sys",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "event_id": "used:cc:69651ebbf736a3c5:f694bb3809f31a43:abb9a54dbbb5546d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
      "pid": 906917,
      "sha256": "7f90412cf2ad6caa6bdc5e95b229fb00eaa8514d4fa5c12390d1aa09ea75ef3f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ducc-sys",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "event_id": "used:cc:69651ebbf736a3c5:0c3ab9a381145413:abb9a54dbbb5546d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
      "pid": 906917,
      "sha256": "8335479aab6d0505c484661a5ba388f20d3ec4110223dc32f606744e099fe03c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ducc-sys",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "event_id": "used:cc:69651ebbf736a3c5:59ea4e824b7aca79:abb9a54dbbb5546d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
      "pid": 906917,
      "sha256": "ae52d18772ff8aa7cec8b14f73b369280c72261717d71592b0db6378f0d8a596",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ducc-sys",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "event_id": "used:cc:69651ebbf736a3c5:81b425daf9c30482:abb9a54dbbb5546d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
      "pid": 906917,
      "sha256": "ebb840d8cd1c2450f9aeb6da8e1e2f6080f4f8c141b4290591e40882d407cc38",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ducc-sys",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "event_id": "used:cc:69651ebbf736a3c5:0893b53b667c2da4:abb9a54dbbb5546d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
      "pid": 906917,
      "sha256": "284d84f7f81d89ec89645b2a82d086f655ecc90a264df977b30b9207cf79cd39",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
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
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "cargo_pkg_name": "ducc-sys",
      "cargo_pkg_version": "0.1.2",
      "context_path": "/tmp/native-trace-906565-1783998293152/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-906565-1783998293152/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 906917,
      "ppid": 906903,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-5ab4653aa6383c98.rlib",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
        "/target/debug/deps",
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
          "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV",
          "kind": "object",
          "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
          "kind": "object",
          "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
          "kind": "object",
          "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
          "kind": "object",
          "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
          "kind": "object",
          "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
          "kind": "object",
          "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
          "kind": "object",
          "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
          "kind": "object",
          "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
          "kind": "object",
          "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
          "kind": "object",
          "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.00.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.02.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.03.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.01.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.04.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.05.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.06.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.07.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.08.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-5ab4653aa6383c98.rlib(cc-5ab4653aa6383c98.cc.6f0b04c7e737fb26-cgu.09.rcgu.o",
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
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib(hashbrown-1448c95121de53aa.hashbrown.c0386ddbfadcbbc1-cgu.0.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-906917-1783998295538715164.map",
      "pid": 906917,
      "ppid": 906903,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-906917-1783998295538715164.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
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
      "parsed_event_count": 78,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 79,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "0.102   TIME(s) PCOMM            PID    PPID   RET ARGS\ncargo            906879 906565   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n0.114   rustc            906880 906879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n0.134   rustc            906886 906879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.45/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"num_cpus\", \"parallel\")) -C metadata=9e0bc4e1d16e6475 ...\n0.470   rustc            906903 906879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"bindgen\", \"build-ffi-gen\", \"use-exec-timeout-check\")) -C metadata=4b2b2b459039c355 ...\n0.507   cc               906917 906903   0 /tmp/native-trace-906565-1783998293152/shims/cc -m64 /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-5ab4653aa6383c98.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd ...\n0.507   cc               906918 906917   0 /usr/bin/cc -m64 /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcE3NPdV/symbols.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0u1bfp1.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0u1bfp1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-5ab4653aa6383c98.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd ...\n0.510   collect2         906919 906918   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccFLL6V3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.511   ld.lld           906920 906919   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccFLL6V3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0 ...\n0.512   rust-lld         906920 906919   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccFLL6V3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.561   build-script-bu  906938 906879   0 /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build-script-build\n0.563   aarch64-linux-g  906939 906938   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -I duktape -Wall -Wextra -std=c99 -o /target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o -c duktape/duktape.c\n0.564   cc1              906941 906939   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I duktape -imultiarch aarch64-linux-gnu duktape/duktape.c -quiet -dumpbase duktape.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o -g -O0 -Wall -Wextra -std=c99 -ffunction-sections ...\n0.857   cargo            906942 906802   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n0.869   rustc            906943 906942   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n0.889   rustc            906949 906942   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.45/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"num_cpus\", \"parallel\")) -C metadata=9e0bc4e1d16e6475 ...\n1.220   rustc            906966 906942   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"bindgen\", \"build-ffi-gen\", \"use-exec-timeout-check\")) -C metadata=4b2b2b459039c355 ...\n1.254   cc               906980 906966   0 /tmp/native-trace-906802-1783998293688/shims/cc -m64 /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustclk1esL/symbols.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0mpxqxh.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-5ab4653aa6383c98.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd ...\n1.255   cc               906981 906980   0 /usr/bin/cc -m64 /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustclk1esL/symbols.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.0mpxqxh.rcgu.o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.0mpxqxh.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-5ab4653aa6383c98.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd ...\n1.257   collect2         906982 906981   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1nG5Va.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n1.258   ld.lld           906983 906982   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1nG5Va.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0 ...\n1.258   rust-lld         906983 906982   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1nG5Va.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n1.301   build-script-bu  907001 906942   0 /target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build-script-build\n1.303   riscv64-linux-g  907002 907001   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -g -fno-omit-frame-pointer -march=rv64gc -mabi=lp64 -I duktape -Wall -Wextra -std=c99 -o /target/riscv64gc-unknown-linux-gnu/debug/build/ducc-sys-c5bedf43582ed6cc/out/duktape/duktape.o -c duktape/duktape.c\n1.304   cc1              907004 907002   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I duktape -imultilib . -imultiarch riscv64-linux-gnu duktape/duktape.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/ducc-sys-c5bedf43582ed6cc/out/duktape/ -dumpbase duktape.c -dumpbase-ext .c -march=rv64gc -mabi=lp64 -misa-spec=2.2 -march=rv64imafdc ...\n1.774   as               907005 906939   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I duktape -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o /tmp/ccEwwpWH.s\n1.998   aarch64-linux-g  907006 906938   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -I duktape -Wall -Wextra -std=c99 -o /target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o -c duktape/wrapper.c\n1.999   cc1              907008 907006   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I duktape -imultiarch aarch64-linux-gnu duktape/wrapper.c -quiet -dumpbase wrapper.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o -g -O0 -Wall -Wextra -std=c99 -ffunction-sections ...\n2.034   as               907009 907006   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I duktape -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o /tmp/cc70r4DI.s\n2.046   aarch64-linux-g  907010 906938   0 /usr/bin/aarch64-linux-gnu-ar crs /target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/libduktape.a /target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o /target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o\n2.054   rustc            907013 906879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ducc_sys --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"bindgen\", \"build-ffi-gen\", \"use-exec-timeout-check\")) -C metadata=f68ba6762b7286e5 ...\n5.779   runc             907021 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process1242725692 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n5.785   exe              907029 907021   0 /proc/self/exe init\n5.800   curl             907031 907021   0 /usr/bin/curl -f http://localhost:9091/healthz\n7.846   sh               907038 2147557   0 /bin/sh -c which ps\n7.847   which            907038 2147557   0 /usr/bin/which ps\n7.849   sh               907039 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n7.850   ps               907039 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n7.872   sh               907040 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n7.873   cpuUsage.sh      907040 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n7.874   sed              907041 907040   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n7.875   cat              907042 907040   0 /usr/bin/cat /proc/2240539/stat\n7.876   cat              907043 907040   0 /usr/bin/cat /proc/4193716/stat\n7.877   sleep            907044 907040   0 /usr/bin/sleep 1\n8.879   sed              907045 907040   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n8.882   cat              907046 907040   0 /usr/bin/cat /proc/2240539/stat\n8.885   cat              907048 907040   0 /usr/bin/cat /proc/4193716/stat\n9.369   16               907050 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n9.381   frpc             907050 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n12.849  sh               907056 2147557   0 /bin/sh -c which ps\n12.850  which            907056 2147557   0 /usr/bin/which ps\n12.853  sh               907057 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n12.854  ps               907057 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n12.884  sh               907058 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n12.885  cpuUsage.sh      907058 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n12.886  sed              907059 907058   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n12.889  cat              907060 907058   0 /usr/bin/cat /proc/2240539/stat\n12.890  cat              907061 907058   0 /usr/bin/cat /proc/4193716/stat\n12.891  sleep            907062 907058   0 /usr/bin/sleep 1\n13.894  sed              907063 907058   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n13.896  cat              907064 907058   0 /usr/bin/cat /proc/2240539/stat\n13.899  cat              907066 907058   0 /usr/bin/cat /proc/4193716/stat\n14.746  runc             907068 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process1305497709 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n14.752  exe              907075 907068   0 /proc/self/exe init\n14.785  curl             907078 907068   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n17.262  runc             907084 905159   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b37b484559c5e0a6efd41fe438558e681a2ec89c29eded851e201dffdac --log-format json --systemd-cgroup kill --all b37b484559c5e0a6efd41fe438558e681a2ec89c29eded851e201dffdacc59d7 9\n17.270  runc             907091 905159   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b37b484559c5e0a6efd41fe438558e681a2ec89c29eded851e201dffdac --log-format json --systemd-cgroup delete b37b484559c5e0a6efd41fe438558e681a2ec89c29eded851e201dffdacc59d7\n17.453  containerd-shim  907097 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id b37b484559c5e0a6efd41fe438558e681a2ec89c29eded851e201dffdacc59d7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b37b484559c5e0a6efd41fe438558e681a2ec89c29eded851e201dffdac delete\n17.456  runc             907104 907097   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b37b484559c5e0a6efd41fe438558e681a2ec89c29eded851e201dffdacc59d --log-format json delete --force b37b484559c5e0a6efd41fe438558e681a2ec89c29eded851e201dffdacc59d7\n17.501  sh               907112 907109   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth45c2496\n17.502  ethtool          907113 907112   0 /usr/sbin/ethtool -i veth45c2496\n17.502  sed              907114 907112   0 /usr/bin/sed -n s/^driver: //p\n17.509  systemd-sysctl   907117 907109   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth45c2496 --prefix=/net/ipv4/neigh/veth45c2496 --prefix=/net/ipv6/conf/veth45c2496 --prefix=/net/ipv6/neigh/veth45c2496\n18.362  runc             907119 906740   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/569e55617dec3b92ea9a4e2260a682a72353cf3ffeb9c98611815f89c84 --log-format json --systemd-cgroup kill --all 569e55617dec3b92ea9a4e2260a682a72353cf3ffeb9c98611815f89c847d45b 9\n18.381  runc             907125 906740   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/569e55617dec3b92ea9a4e2260a682a72353cf3ffeb9c98611815f89c84 --log-format json --systemd-cgroup delete 569e55617dec3b92ea9a4e2260a682a72353cf3ffeb9c98611815f89c847d45b\n18.577  containerd-shim  907131 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 569e55617dec3b92ea9a4e2260a682a72353cf3ffeb9c98611815f89c847d45b -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/569e55617dec3b92ea9a4e2260a682a72353cf3ffeb9c98611815f89c84 delete\n18.580  runc             907137 907131   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/569e55617dec3b92ea9a4e2260a682a72353cf3ffeb9c98611815f89c847d45 --log-format json delete --force 569e55617dec3b92ea9a4e2260a682a72353cf3ffeb9c98611815f89c847d45b\n18.617  systemd-sysctl   907143 907109   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb74b48e --prefix=/net/ipv4/neigh/vethb74b48e --prefix=/net/ipv6/conf/vethb74b48e --prefix=/net/ipv6/neigh/vethb74b48e\n18.659  rustup           907146 906576   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n"
    },
    {
      "argv": [
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 906938,
      "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build-script-build",
      "pid": 906938,
      "ppid": 906879,
      "root_cargo_pid": 906879,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-fno-omit-frame-pointer",
        "-I",
        "duktape",
        "-Wall",
        "-Wextra",
        "-std=c99",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o",
        "-c",
        "duktape/duktape.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 906938,
      "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 906939,
      "ppid": 906938,
      "root_cargo_pid": 906879,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "duktape",
        "-imultiarch",
        "aarch64-linux-gnu",
        "duktape/duktape.c",
        "-quiet",
        "-dumpbase",
        "duktape.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o",
        "-g",
        "-O0",
        "-Wall",
        "-Wextra",
        "-std=c99",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 906938,
      "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 906941,
      "ppid": 906939,
      "root_cargo_pid": 906879,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-I",
        "duktape",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o",
        "/tmp/ccEwwpWH.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 906938,
      "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 907005,
      "ppid": 906939,
      "root_cargo_pid": 906879,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-fno-omit-frame-pointer",
        "-I",
        "duktape",
        "-Wall",
        "-Wextra",
        "-std=c99",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o",
        "-c",
        "duktape/wrapper.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 906938,
      "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 907006,
      "ppid": 906938,
      "root_cargo_pid": 906879,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "duktape",
        "-imultiarch",
        "aarch64-linux-gnu",
        "duktape/wrapper.c",
        "-quiet",
        "-dumpbase",
        "wrapper.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o",
        "-g",
        "-O0",
        "-Wall",
        "-Wextra",
        "-std=c99",
        "-ffunction-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 906938,
      "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 907008,
      "ppid": 907006,
      "root_cargo_pid": 906879,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-I",
        "duktape",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o",
        "/tmp/cc70r4DI.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 906938,
      "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 907009,
      "ppid": 907006,
      "root_cargo_pid": 906879,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "crs",
        "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/libduktape.a",
        "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 906938,
      "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 907010,
      "ppid": 906938,
      "root_cargo_pid": 906879,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "ducc-sys",
      "cwd": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "event_id": "bsrun:91b8913f305db1e2:e9794bf2d1e8e296:c38049f959723422",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
      "out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
      "success": true,
      "target": null,
      "version": "0.1.2",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
  "item": {
    "rank": 3590,
    "crate": "ducc-sys",
    "version": "0.1.2",
    "crate_id": "166348",
    "version_id": "181942",
    "downloads": 2709827,
    "cumulative_downloads": 108740028979,
    "cumulative_share_of_global": 0.40655386508444935,
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
