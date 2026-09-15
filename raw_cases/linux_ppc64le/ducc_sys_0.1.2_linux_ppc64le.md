# `ducc-sys` `0.1.2`

Platform: Linux ppc64le

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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D",
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
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-907958-1783998324646487919.map",
  "pid": 907958,
  "ppid": 907944,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-907958-1783998324646487919.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/libduktape.a`

Owner: `ducc-sys` `0.1.2`

### Source files

* `/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2/duktape/duktape.c`
* `/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2/duktape/wrapper.c`

### Source acquisition records

_None._

### Source preparation records

#### Record 1

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "duktape",
    "-Wall",
    "-Wextra",
    "-std=c99",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/duktape.o",
    "-c",
    "duktape/duktape.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 907979,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 907980,
  "ppid": 907979,
  "root_cargo_pid": 907920,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 2

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "duktape",
    "-Wall",
    "-Wextra",
    "-std=c99",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/wrapper.o",
    "-c",
    "duktape/wrapper.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 907979,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 909769,
  "ppid": 907979,
  "root_cargo_pid": 907920,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

### Compilation records

#### Record 1

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "duktape",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "duktape/wrapper.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "wrapper.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/wrapper.o",
    "-g",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c99",
    "..."
  ],
  "src": "duktape/wrapper.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/wrapper.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 909772,
  "ppid": 909769,
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "root_cargo_pid": 907920,
  "build_script_root_pid": 907979,
  "build_script_related": true,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 2

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "duktape",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "duktape/duktape.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "duktape.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/duktape.o",
    "-g",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c99",
    "..."
  ],
  "src": "duktape/duktape.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/duktape.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 907982,
  "ppid": 907980,
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "root_cargo_pid": 907920,
  "build_script_root_pid": 907979,
  "build_script_related": true,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

### Archive records

#### Record 1

```json
{
  "event": "archive",
  "tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "real_tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "crs",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/libduktape.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/duktape.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/wrapper.o"
  ],
  "archive": "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/libduktape.a",
  "objects": [
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/duktape.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/wrapper.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 909808,
  "ppid": 907979,
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "root_cargo_pid": 907920,
  "build_script_root_pid": 907979,
  "build_script_related": true,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
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
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "workspace_root": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2"
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
      "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
      "name": "ducc-sys",
      "version": "0.1.2",
      "manifest_path": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2"
    }
  ],
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 907958,
  "ppid": 907944,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "event_id": "used:cc:dc0fbd77f45cb46c:69e8ac90c34f6124:abb9a54dbbb5546d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
  "pid": 907958,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "event_id": "used:cc:dc0fbd77f45cb46c:8a54b996bba58cb4:abb9a54dbbb5546d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
  "pid": 907958,
  "sha256": "346f6d2a2528d0c14006f68510c1c3b9a8637371a9c90989c60a418f813aca51",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "event_id": "used:cc:dc0fbd77f45cb46c:40f996abc67c6f98:abb9a54dbbb5546d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
  "pid": 907958,
  "sha256": "0fb7db419fcc39e08a9a814c582815d3ab5e3cece80adc390e1f7debc1ac6620",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "event_id": "used:cc:dc0fbd77f45cb46c:37c2a3a7705290f5:abb9a54dbbb5546d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
  "pid": 907958,
  "sha256": "62ba6c84c574754c5b9bd516f89d25e5bbcf8dcbaa33be5c7545e8ea8f606c2f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "event_id": "used:cc:dc0fbd77f45cb46c:941f39cb98da0565:abb9a54dbbb5546d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
  "pid": 907958,
  "sha256": "0793ecd52b02b367c3e8301aa3e0669748f0841ca85b9236036753e5307c13f9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "event_id": "used:cc:dc0fbd77f45cb46c:5ffca30112cf448f:abb9a54dbbb5546d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
  "pid": 907958,
  "sha256": "664dde5bbe3133d5c6ebef5b89e77038edf725052864088dab417801fd9b0426",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "event_id": "used:cc:dc0fbd77f45cb46c:9187198a8a9194cb:abb9a54dbbb5546d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
  "pid": 907958,
  "sha256": "f22f750d5f09eacafe24bce68c264046083966729234f5a0cc7ff769b5c1b6b8",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "event_id": "used:cc:dc0fbd77f45cb46c:62be1296121fc2ba:abb9a54dbbb5546d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
  "pid": 907958,
  "sha256": "21b31eee47c7e0f8527f38f25e8faf3e654615620caf813bcab2bb1dd15c4ea8",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "event_id": "used:cc:dc0fbd77f45cb46c:449b985c08504841:abb9a54dbbb5546d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
  "pid": 907958,
  "sha256": "e2abe076b985185ea62e90a719d96e9a00d2eba63d5708420d7e8f727189d79f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "event_id": "used:cc:dc0fbd77f45cb46c:96c88e888e2cdb82:abb9a54dbbb5546d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
  "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
  "pid": 907958,
  "sha256": "284d84f7f81d89ec89645b2a82d086f655ecc90a264df977b30b9207cf79cd39",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "cargo_pkg_name": "ducc-sys",
  "cargo_pkg_version": "0.1.2",
  "context_path": "/tmp/native-trace-907500-1783998322173/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-907500-1783998322173/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 907958,
  "ppid": 907944,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D",
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
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
      "kind": "object",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-907958-1783998324646487919.map",
  "pid": 907958,
  "ppid": 907944,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-907958-1783998324646487919.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
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
  "parsed_event_count": 797,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 798,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "eck-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v3_24\")) -C metadata=202d1b00c29966b2 ...\n9.724   rustc            911752 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gio-sys-0.18.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"v2_58\" --cfg feature=\"v2_60\" --cfg feature=\"v2_62\" ...\n9.728   rustc            911754 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atk-sys-0.18.2/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_30\", \"v2_32\", \"v2_34\", \"v2_38\", \"v2_46\", \"v2_50\")) -C metadata=c71e96213c395258 ...\n9.730   rustc            911758 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gdk-pixbuf-sys-0.18.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_40\", \"v2_42\")) -C metadata=d4fbec7ded70d8d5 ...\n9.733   rustc            911761 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cairo-sys-rs-0.18.2/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"glib\" --cfg feature=\"use_glib\" --check-cfg cfg(docsrs,test) ...\n9.735   rustc            911766 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pango-sys-0.18.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v1_42\", \"v1_44\", \"v1_46\", \"v1_48\", \"v1_50\", \"v1_52\")) -C metadata=95760bdc691fca0e ...\n9.739   rustc            911771 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gtk-sys-0.18.2/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v3_24\", \"v3_24_1\", \"v3_24_11\", \"v3_24_30\", \"v3_24_8\", \"v3_24_9\")) -C metadata=3e92667b2ec628fc ...\n9.746   rustc            911775 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/javascriptcore-rs-sys-1.1.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"v2_28\" --cfg feature=\"v2_38\" --check-cfg cfg(docsrs,test) ...\n9.747   rustc            911779 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/webkit2gtk-sys-2.0.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"v2_10\" --cfg feature=\"v2_12\" --cfg feature=\"v2_14\" ...\n9.751   rustc            911788 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/soup3-sys-0.5.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"v3_0\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v3_0\", \"v3_2\", \"v3_4\")) ...\n9.757   rustc            911792 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gdkx11-sys-0.18.2/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"cairo\", \"v3_24\", \"v3_24_2\")) -C metadata=ef98f6ac76597b4e ...\n9.769   rustc            911801 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-2.0.17/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n9.780   cc               911818 911748   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/gobject-sys-f6b59444a30ac5fd/rustci1j3SE/symbols.o /target/debug/build/gobject-sys-f6b59444a30ac5fd/build_script_build-f6b59444a30ac5fd.build_script_build.d0d5cd41697241e1-cgu.0.r /target/debug/build/gobject-sys-f6b59444a30ac5fd/build_script_build-f6b59444a30ac5fd.1ejsowl0gjxgeidaw5k1o9icb.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.781   cc               911827 911818   0 /usr/bin/cc -m64 /target/debug/build/gobject-sys-f6b59444a30ac5fd/rustci1j3SE/symbols.o /target/debug/build/gobject-sys-f6b59444a30ac5fd/build_script_build-f6b59444a30ac5fd.build_script_build.d0d5cd41697241e1-cgu.0.r /target/debug/build/gobject-sys-f6b59444a30ac5fd/build_script_build-f6b59444a30ac5fd.1ejsowl0gjxgeidaw5k1o9icb.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.787   collect2         911836 911827   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdj9gLN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.789   cc               911829 911747   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/glib-sys-13eedc9ff3bf5907/rustcz0Cv7L/symbols.o /target/debug/build/glib-sys-13eedc9ff3bf5907/build_script_build-13eedc9ff3bf5907.build_script_build.6451c814820afebc-cgu.0.rcgu /target/debug/build/glib-sys-13eedc9ff3bf5907/build_script_build-13eedc9ff3bf5907.5r3gjxdpfb1oqx5yj5m1hiycg.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.791   cc               911844 911829   0 /usr/bin/cc -m64 /target/debug/build/glib-sys-13eedc9ff3bf5907/rustcz0Cv7L/symbols.o /target/debug/build/glib-sys-13eedc9ff3bf5907/build_script_build-13eedc9ff3bf5907.build_script_build.6451c814820afebc-cgu.0.rcgu /target/debug/build/glib-sys-13eedc9ff3bf5907/build_script_build-13eedc9ff3bf5907.5r3gjxdpfb1oqx5yj5m1hiycg.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.791   ld.lld           911845 911836   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdj9gLN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gobject-sys-f6b59444a30ac5fd/build_script_build-f6b59444a30ac5fd ...\n9.792   rust-lld         911845 911836   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdj9gLN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.794   cc               911846 911752   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/gio-sys-1684b809e16c705c/rustcqSHqbF/symbols.o /target/debug/build/gio-sys-1684b809e16c705c/build_script_build-1684b809e16c705c.build_script_build.a0581cef4741dae2-cgu.0.rcgu. /target/debug/build/gio-sys-1684b809e16c705c/build_script_build-1684b809e16c705c.8tzr4a6zzknzo0jtyu7yuqacq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.794   cc               911848 911846   0 /usr/bin/cc -m64 /target/debug/build/gio-sys-1684b809e16c705c/rustcqSHqbF/symbols.o /target/debug/build/gio-sys-1684b809e16c705c/build_script_build-1684b809e16c705c.build_script_build.a0581cef4741dae2-cgu.0.rcgu. /target/debug/build/gio-sys-1684b809e16c705c/build_script_build-1684b809e16c705c.8tzr4a6zzknzo0jtyu7yuqacq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.797   collect2         911849 911844   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRQ0cNp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.799   ld.lld           911854 911849   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRQ0cNp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/glib-sys-13eedc9ff3bf5907/build_script_build-13eedc9ff3bf5907 ...\n9.802   collect2         911855 911848   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccY8aKtv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.803   ld.lld           911861 911855   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccY8aKtv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gio-sys-1684b809e16c705c/build_script_build-1684b809e16c705c ...\n9.803   cc               911852 911758   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/gdk-pixbuf-sys-99ebdd3ff39c8a38/rustcejLWWf/symbols.o /target/debug/build/gdk-pixbuf-sys-99ebdd3ff39c8a38/build_script_build-99ebdd3ff39c8a38.build_script_build.575621406988ce8a-cgu. /target/debug/build/gdk-pixbuf-sys-99ebdd3ff39c8a38/build_script_build-99ebdd3ff39c8a38.0gc3kvsel0ddnoaovevnxq06g.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.804   rust-lld         911854 911849   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRQ0cNp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.804   cc               911860 911775   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/javascriptcore-rs-sys-ce8b621aa6c5c06b/rustc9z5Wn8/symbols.o /target/debug/build/javascriptcore-rs-sys-ce8b621aa6c5c06b/build_script_build-ce8b621aa6c5c06b.build_script_build.2fa4af6a5ed431 /target/debug/build/javascriptcore-rs-sys-ce8b621aa6c5c06b/build_script_build-ce8b621aa6c5c06b.215bhjjcgyw5qlx6j2a947tcu.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.805   rust-lld         911861 911855   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccY8aKtv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.805   cc               911862 911860   0 /usr/bin/cc -m64 /target/debug/build/javascriptcore-rs-sys-ce8b621aa6c5c06b/rustc9z5Wn8/symbols.o /target/debug/build/javascriptcore-rs-sys-ce8b621aa6c5c06b/build_script_build-ce8b621aa6c5c06b.build_script_build.2fa4af6a5ed431 /target/debug/build/javascriptcore-rs-sys-ce8b621aa6c5c06b/build_script_build-ce8b621aa6c5c06b.215bhjjcgyw5qlx6j2a947tcu.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.808   cc               911856 911779   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/webkit2gtk-sys-a2274efebb511770/rustc4pZ38n/symbols.o /target/debug/build/webkit2gtk-sys-a2274efebb511770/build_script_build-a2274efebb511770.build_script_build.1fd31a54239f2e4e-cgu. /target/debug/build/webkit2gtk-sys-a2274efebb511770/build_script_build-a2274efebb511770.9wvt76o3y6mlkcnqlh9ps0cwj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.808   cc               911863 911771   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/gtk-sys-1445a9c1b87c9ffd/rustcLF5MxP/symbols.o /target/debug/build/gtk-sys-1445a9c1b87c9ffd/build_script_build-1445a9c1b87c9ffd.build_script_build.6848d2929f0f347-cgu.0.rcgu.o /target/debug/build/gtk-sys-1445a9c1b87c9ffd/build_script_build-1445a9c1b87c9ffd.cykgw98lh10eaffzuurmnl430.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.809   cc               911864 911852   0 /usr/bin/cc -m64 /target/debug/build/gdk-pixbuf-sys-99ebdd3ff39c8a38/rustcejLWWf/symbols.o /target/debug/build/gdk-pixbuf-sys-99ebdd3ff39c8a38/build_script_build-99ebdd3ff39c8a38.build_script_build.575621406988ce8a-cgu. /target/debug/build/gdk-pixbuf-sys-99ebdd3ff39c8a38/build_script_build-99ebdd3ff39c8a38.0gc3kvsel0ddnoaovevnxq06g.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.809   cc               911867 911856   0 /usr/bin/cc -m64 /target/debug/build/webkit2gtk-sys-a2274efebb511770/rustc4pZ38n/symbols.o /target/debug/build/webkit2gtk-sys-a2274efebb511770/build_script_build-a2274efebb511770.build_script_build.1fd31a54239f2e4e-cgu. /target/debug/build/webkit2gtk-sys-a2274efebb511770/build_script_build-a2274efebb511770.9wvt76o3y6mlkcnqlh9ps0cwj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.810   cc               911868 911863   0 /usr/bin/cc -m64 /target/debug/build/gtk-sys-1445a9c1b87c9ffd/rustcLF5MxP/symbols.o /target/debug/build/gtk-sys-1445a9c1b87c9ffd/build_script_build-1445a9c1b87c9ffd.build_script_build.6848d2929f0f347-cgu.0.rcgu.o /target/debug/build/gtk-sys-1445a9c1b87c9ffd/build_script_build-1445a9c1b87c9ffd.cykgw98lh10eaffzuurmnl430.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.811   collect2         911870 911864   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccevTAIy.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.811   collect2         911866 911862   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRdw3Xo.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.812   collect2         911873 911867   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYTbluS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.812   ld.lld           911874 911870   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccevTAIy.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gdk-pixbuf-sys-99ebdd3ff39c8a38/build_script_build-99ebdd3ff39c8a38 ...\n9.813   cc               911869 911754   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/atk-sys-502a086b1a88df78/rustct8Qmor/symbols.o /target/debug/build/atk-sys-502a086b1a88df78/build_script_build-502a086b1a88df78.build_script_build.e0777fba1caca75b-cgu.0.rcgu. /target/debug/build/atk-sys-502a086b1a88df78/build_script_build-502a086b1a88df78.dwpbrm16i3lvcla693c2936s3.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.813   ld.lld           911877 911873   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYTbluS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/webkit2gtk-sys-a2274efebb511770/build_script_build-a2274efebb511770 ...\n9.814   ld.lld           911875 911866   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRdw3Xo.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/javascriptcore-rs-sys-ce8b621aa6c5c06b/build_script_build-ce8b621aa6c5c06b ...\n9.815   rust-lld         911875 911866   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRdw3Xo.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.816   cc               911878 911751   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/gdk-sys-f3a56defaf3a0eaf/rustcIbWzzU/symbols.o /target/debug/build/gdk-sys-f3a56defaf3a0eaf/build_script_build-f3a56defaf3a0eaf.build_script_build.a42b15eba3e5156e-cgu.0.rcgu. /target/debug/build/gdk-sys-f3a56defaf3a0eaf/build_script_build-f3a56defaf3a0eaf.7xwcczdwaqjhoji1lgnm2g4j7.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.816   cc               911879 911761   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/cairo-sys-rs-6cc82f16880d1516/rustcSo2kCJ/symbols.o /target/debug/build/cairo-sys-rs-6cc82f16880d1516/build_script_build-6cc82f16880d1516.build_script_build.d5684fed48f9187f-cgu.0. /target/debug/build/cairo-sys-rs-6cc82f16880d1516/build_script_build-6cc82f16880d1516.45mydky3bdut8e76j1f93kag5.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.817   cc               911883 911879   0 /usr/bin/cc -m64 /target/debug/build/cairo-sys-rs-6cc82f16880d1516/rustcSo2kCJ/symbols.o /target/debug/build/cairo-sys-rs-6cc82f16880d1516/build_script_build-6cc82f16880d1516.build_script_build.d5684fed48f9187f-cgu.0. /target/debug/build/cairo-sys-rs-6cc82f16880d1516/build_script_build-6cc82f16880d1516.45mydky3bdut8e76j1f93kag5.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.817   cc               911882 911878   0 /usr/bin/cc -m64 /target/debug/build/gdk-sys-f3a56defaf3a0eaf/rustcIbWzzU/symbols.o /target/debug/build/gdk-sys-f3a56defaf3a0eaf/build_script_build-f3a56defaf3a0eaf.build_script_build.a42b15eba3e5156e-cgu.0.rcgu. /target/debug/build/gdk-sys-f3a56defaf3a0eaf/build_script_build-f3a56defaf3a0eaf.7xwcczdwaqjhoji1lgnm2g4j7.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.817   rust-lld         911877 911873   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYTbluS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.817   collect2         911885 911868   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccsmJftb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.819   cc               911880 911869   0 /usr/bin/cc -m64 /target/debug/build/atk-sys-502a086b1a88df78/rustct8Qmor/symbols.o /target/debug/build/atk-sys-502a086b1a88df78/build_script_build-502a086b1a88df78.build_script_build.e0777fba1caca75b-cgu.0.rcgu. /target/debug/build/atk-sys-502a086b1a88df78/build_script_build-502a086b1a88df78.dwpbrm16i3lvcla693c2936s3.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.821   collect2         911903 911882   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjQeh8H.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.821   ld.lld           911901 911885   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccsmJftb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gtk-sys-1445a9c1b87c9ffd/build_script_build-1445a9c1b87c9ffd ...\n9.821   cc               911881 911766   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/pango-sys-36f28451941192e1/rustcxI1Paf/symbols.o /target/debug/build/pango-sys-36f28451941192e1/build_script_build-36f28451941192e1.build_script_build.d9a5aede8f97695c-cgu.0.rcg /target/debug/build/pango-sys-36f28451941192e1/build_script_build-36f28451941192e1.8nn9rl2xnlpb96kn2sj9djk4q.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.821   collect2         911902 911883   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbdaX6D.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.821   rust-lld         911874 911870   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccevTAIy.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.822   cc               911904 911881   0 /usr/bin/cc -m64 /target/debug/build/pango-sys-36f28451941192e1/rustcxI1Paf/symbols.o /target/debug/build/pango-sys-36f28451941192e1/build_script_build-36f28451941192e1.build_script_build.d9a5aede8f97695c-cgu.0.rcg /target/debug/build/pango-sys-36f28451941192e1/build_script_build-36f28451941192e1.8nn9rl2xnlpb96kn2sj9djk4q.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.822   ld.lld           911905 911903   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjQeh8H.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gdk-sys-f3a56defaf3a0eaf/build_script_build-f3a56defaf3a0eaf ...\n9.823   ld.lld           911906 911902   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbdaX6D.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/cairo-sys-rs-6cc82f16880d1516/build_script_build-6cc82f16880d1516 ...\n9.823   rust-lld         911901 911885   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccsmJftb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.824   rust-lld         911906 911902   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbdaX6D.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.825   collect2         911908 911904   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYp2r12.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.826   ld.lld           911910 911908   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYp2r12.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/pango-sys-36f28451941192e1/build_script_build-36f28451941192e1 ...\n9.828   rust-lld         911910 911908   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYp2r12.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.829   cc               911911 911792   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/gdkx11-sys-22d82cfc3eab7e16/rustcQ47B2S/symbols.o /target/debug/build/gdkx11-sys-22d82cfc3eab7e16/build_script_build-22d82cfc3eab7e16.build_script_build.6c555fbe42f1d7cc-cgu.0.rc /target/debug/build/gdkx11-sys-22d82cfc3eab7e16/build_script_build-22d82cfc3eab7e16.5jquqezoauzbkufumiqz4v4ub.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.830   rust-lld         911905 911903   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjQeh8H.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.830   collect2         911907 911880   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccV2rUvj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.833   cc               911909 911788   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/soup3-sys-49050de6244188ec/rustc8cGpDI/symbols.o /target/debug/build/soup3-sys-49050de6244188ec/build_script_build-49050de6244188ec.build_script_build.54104c911d6b3057-cgu.0.rcg /target/debug/build/soup3-sys-49050de6244188ec/build_script_build-49050de6244188ec.b2eyhow29j9z2uu5qju0hocd0.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.833   cc               911912 911911   0 /usr/bin/cc -m64 /target/debug/build/gdkx11-sys-22d82cfc3eab7e16/rustcQ47B2S/symbols.o /target/debug/build/gdkx11-sys-22d82cfc3eab7e16/build_script_build-22d82cfc3eab7e16.build_script_build.6c555fbe42f1d7cc-cgu.0.rc /target/debug/build/gdkx11-sys-22d82cfc3eab7e16/build_script_build-22d82cfc3eab7e16.5jquqezoauzbkufumiqz4v4ub.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.834   cc               911915 911909   0 /usr/bin/cc -m64 /target/debug/build/soup3-sys-49050de6244188ec/rustc8cGpDI/symbols.o /target/debug/build/soup3-sys-49050de6244188ec/build_script_build-49050de6244188ec.build_script_build.54104c911d6b3057-cgu.0.rcg /target/debug/build/soup3-sys-49050de6244188ec/build_script_build-49050de6244188ec.b2eyhow29j9z2uu5qju0hocd0.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.835   ld.lld           911913 911907   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccV2rUvj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/atk-sys-502a086b1a88df78/build_script_build-502a086b1a88df78 ...\n9.836   collect2         911931 911912   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cctBZT6a.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.838   rust-lld         911913 911907   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccV2rUvj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.838   collect2         911932 911915   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7RWLho.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.840   ld.lld           911933 911931   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cctBZT6a.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gdkx11-sys-22d82cfc3eab7e16/build_script_build-22d82cfc3eab7e16 ...\n9.840   ld.lld           911934 911932   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7RWLho.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/soup3-sys-49050de6244188ec/build_script_build-49050de6244188ec ...\n9.843   rust-lld         911933 911931   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cctBZT6a.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.843   rust-lld         911934 911932   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7RWLho.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n10.095  build-script-bu  912117 908551   0 /target/debug/build/glib-sys-13eedc9ff3bf5907/build-script-build\n10.098  pkg-config       912120 912117   0 /tmp/native-trace-907906-1783998323002/shims/pkg-config --libs --cflags glib-2.0 glib-2.0 >= 2.70\n10.098  pkg-config       912121 912120   0 /usr/bin/pkg-config --libs --cflags glib-2.0 glib-2.0 >= 2.70\n10.099  build-script-bu  912119 908551   0 /target/debug/build/gobject-sys-f6b59444a30ac5fd/build-script-build\n10.102  pkg-config       912123 912119   0 /tmp/native-trace-907906-1783998323002/shims/pkg-config --libs --cflags gobject-2.0 gobject-2.0 >= 2.70\n10.103  pkg-config       912125 912123   0 /usr/bin/pkg-config --libs --cflags gobject-2.0 gobject-2.0 >= 2.70\n10.105  build-script-bu  912124 908551   0 /target/debug/build/cairo-sys-rs-6cc82f16880d1516/build-script-build\n10.108  pkg-config       912126 912124   0 /tmp/native-trace-907906-1783998323002/shims/pkg-config --libs --cflags cairo cairo >= 1.14\n10.109  pkg-config       912127 912126   0 /usr/bin/pkg-config --libs --cflags cairo cairo >= 1.14\n10.764  16               912155 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n10.775  cc               912156 911120   0 /tmp/native-trace-907723-1783998322683/shims/cc -Wl,--version-script=/target/debug/deps/rustcNu352o/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcNu352o/symbols.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.00.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.01.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.02.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.03.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.04.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.05.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.06.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.07.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.08.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.09.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.10.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.11.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.12.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.13.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.14.rcgu.o ...\n10.776  frpc             912155 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n10.776  cc               912158 912156   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcNu352o/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcNu352o/symbols.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.00.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.01.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.02.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.03.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.04.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.05.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.06.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.07.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.08.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.09.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.10.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.11.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.12.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.13.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.14.rcgu.o ...\n10.779  collect2         912165 912158   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDQtDjk.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libglib_macros-7780edfb62714916.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcNu352o/raw-dylibs ...\n10.780  ld.lld           912166 912165   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDQtDjk.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libglib_macros-7780edfb62714916.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcNu352o/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n10.781  rust-lld         912166 912165   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDQtDjk.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libglib_macros-7780edfb62714916.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n11.068  cc               912196 911647   0 /tmp/native-trace-907906-1783998323002/shims/cc -Wl,--version-script=/target/debug/deps/rustc1ECWOY/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc1ECWOY/symbols.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.00.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.01.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.02.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.03.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.04.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.05.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.06.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.07.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.08.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.09.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.10.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.11.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.12.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.13.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.14.rcgu.o ...\n11.069  cc               912197 912196   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc1ECWOY/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc1ECWOY/symbols.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.00.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.01.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.02.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.03.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.04.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.05.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.06.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.07.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.08.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.09.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.10.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.11.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.12.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.13.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.14.rcgu.o ...\n11.072  collect2         912198 912197   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnVVcXE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libglib_macros-7780edfb62714916.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc1ECWOY/raw-dylibs ...\n11.073  ld.lld           912199 912198   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnVVcXE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libglib_macros-7780edfb62714916.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc1ECWOY/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n11.074  rust-lld         912199 912198   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnVVcXE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libglib_macros-7780edfb62714916.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n15.691  runc             912216 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2046224714 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n15.697  exe              912224 912216   0 /proc/self/exe init\n15.728  curl             912226 912216   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n"
}
```

#### Record 18

```json
{
  "argv": [
    "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 907979,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build-script-build",
  "pid": 907979,
  "ppid": 907920,
  "root_cargo_pid": 907920,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out"
}
```

#### Record 19

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "duktape",
    "-Wall",
    "-Wextra",
    "-std=c99",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/duktape.o",
    "-c",
    "duktape/duktape.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 907979,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 907980,
  "ppid": 907979,
  "root_cargo_pid": 907920,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 20

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "duktape",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "duktape/duktape.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "duktape.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/duktape.o",
    "-g",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c99",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 907979,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 907982,
  "ppid": 907980,
  "root_cargo_pid": 907920,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 21

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "duktape",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/duktape.o",
    "/tmp/ccsknfZl.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 907979,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 909640,
  "ppid": 907980,
  "root_cargo_pid": 907920,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 22

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "duktape",
    "-Wall",
    "-Wextra",
    "-std=c99",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/wrapper.o",
    "-c",
    "duktape/wrapper.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 907979,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 909769,
  "ppid": 907979,
  "root_cargo_pid": 907920,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 23

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "duktape",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "duktape/wrapper.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "wrapper.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/wrapper.o",
    "-g",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c99",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 907979,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 909772,
  "ppid": 909769,
  "root_cargo_pid": 907920,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 24

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "duktape",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/wrapper.o",
    "/tmp/cc4Y5utF.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 907979,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 909802,
  "ppid": 909769,
  "root_cargo_pid": 907920,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 25

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "crs",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/libduktape.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/duktape.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/wrapper.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 907979,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 909808,
  "ppid": 907979,
  "root_cargo_pid": 907920,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 26

```json
{
  "crate": "ducc-sys",
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "event_id": "bsrun:a1ba2fddb0656455:e9794bf2d1e8e296:c38049f959723422",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
  "success": true,
  "target": null,
  "version": "0.1.2",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  }
}
```

#### Record 27

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "duktape",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "duktape/duktape.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "duktape.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/duktape.o",
    "-g",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c99",
    "..."
  ],
  "src": "duktape/duktape.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/duktape.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 907982,
  "ppid": 907980,
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "root_cargo_pid": 907920,
  "build_script_root_pid": 907979,
  "build_script_related": true,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 28

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "duktape",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "duktape/wrapper.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "wrapper.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/wrapper.o",
    "-g",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c99",
    "..."
  ],
  "src": "duktape/wrapper.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/wrapper.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 909772,
  "ppid": 909769,
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "root_cargo_pid": 907920,
  "build_script_root_pid": 907979,
  "build_script_related": true,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 29

```json
{
  "event": "archive",
  "tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "real_tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "crs",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/libduktape.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/duktape.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/wrapper.o"
  ],
  "archive": "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/libduktape.a",
  "objects": [
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/duktape.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/wrapper.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 909808,
  "ppid": 907979,
  "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "root_cargo_pid": 907920,
  "build_script_root_pid": 907979,
  "build_script_related": true,
  "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
  "_owner": {
    "crate": "ducc-sys",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
  "_build_script_out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T03:05:50.156333+00:00",
  "crate": "ducc-sys",
  "version": "0.1.2",
  "architecture": "ppc64le",
  "duration_seconds": 32.28825352108106,
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
        "manifest_path": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2/Cargo.toml"
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
      "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "workspace_root": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2"
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
          "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
          "name": "ducc-sys",
          "version": "0.1.2",
          "manifest_path": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2"
        }
      ],
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 907958,
      "ppid": 907944,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "event_id": "used:cc:dc0fbd77f45cb46c:69e8ac90c34f6124:abb9a54dbbb5546d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
      "pid": 907958,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "event_id": "used:cc:dc0fbd77f45cb46c:8a54b996bba58cb4:abb9a54dbbb5546d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
      "pid": 907958,
      "sha256": "346f6d2a2528d0c14006f68510c1c3b9a8637371a9c90989c60a418f813aca51",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "event_id": "used:cc:dc0fbd77f45cb46c:40f996abc67c6f98:abb9a54dbbb5546d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
      "pid": 907958,
      "sha256": "0fb7db419fcc39e08a9a814c582815d3ab5e3cece80adc390e1f7debc1ac6620",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "event_id": "used:cc:dc0fbd77f45cb46c:37c2a3a7705290f5:abb9a54dbbb5546d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
      "pid": 907958,
      "sha256": "62ba6c84c574754c5b9bd516f89d25e5bbcf8dcbaa33be5c7545e8ea8f606c2f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "event_id": "used:cc:dc0fbd77f45cb46c:941f39cb98da0565:abb9a54dbbb5546d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
      "pid": 907958,
      "sha256": "0793ecd52b02b367c3e8301aa3e0669748f0841ca85b9236036753e5307c13f9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "event_id": "used:cc:dc0fbd77f45cb46c:5ffca30112cf448f:abb9a54dbbb5546d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
      "pid": 907958,
      "sha256": "664dde5bbe3133d5c6ebef5b89e77038edf725052864088dab417801fd9b0426",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "event_id": "used:cc:dc0fbd77f45cb46c:9187198a8a9194cb:abb9a54dbbb5546d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
      "pid": 907958,
      "sha256": "f22f750d5f09eacafe24bce68c264046083966729234f5a0cc7ff769b5c1b6b8",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "event_id": "used:cc:dc0fbd77f45cb46c:62be1296121fc2ba:abb9a54dbbb5546d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
      "pid": 907958,
      "sha256": "21b31eee47c7e0f8527f38f25e8faf3e654615620caf813bcab2bb1dd15c4ea8",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "event_id": "used:cc:dc0fbd77f45cb46c:449b985c08504841:abb9a54dbbb5546d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
      "pid": 907958,
      "sha256": "e2abe076b985185ea62e90a719d96e9a00d2eba63d5708420d7e8f727189d79f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "event_id": "used:cc:dc0fbd77f45cb46c:96c88e888e2cdb82:abb9a54dbbb5546d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0",
      "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
      "pid": 907958,
      "sha256": "284d84f7f81d89ec89645b2a82d086f655ecc90a264df977b30b9207cf79cd39",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "cargo_pkg_name": "ducc-sys",
      "cargo_pkg_version": "0.1.2",
      "context_path": "/tmp/native-trace-907500-1783998322173/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-907500-1783998322173/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 907958,
      "ppid": 907944,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D",
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
          "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D",
          "kind": "object",
          "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/rustcy8Dj7D/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
          "kind": "object",
          "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.0q4tchcntaf539bz9hx3giybh.1otbgne.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
          "kind": "object",
          "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.1f4xfv39oiqod3jut7a3pnq83.1otbgne.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
          "kind": "object",
          "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5arm8p5k8ebitjl14ytzz5nl6.1otbgne.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
          "kind": "object",
          "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.5x7wzggd2hxr2g1t9rszv518c.1otbgne.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
          "kind": "object",
          "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.6q4rl89s4pnwfd74vso744rlf.1otbgne.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
          "kind": "object",
          "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.7v1l48g6rbkmyeie793gfqxui.1otbgne.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
          "kind": "object",
          "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.bx0xdjy4flygw6ff7la229xyw.1otbgne.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
          "kind": "object",
          "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.dy8eviw39pby0tjqqnl1i8idl.1otbgne.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0",
          "kind": "object",
          "path": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0.e6s5oh58xyvxetmh9g68l869j.1otbgne.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-907958-1783998324646487919.map",
      "pid": 907958,
      "ppid": 907944,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-907958-1783998324646487919.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
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
      "parsed_event_count": 797,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 798,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "eck-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v3_24\")) -C metadata=202d1b00c29966b2 ...\n9.724   rustc            911752 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gio-sys-0.18.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"v2_58\" --cfg feature=\"v2_60\" --cfg feature=\"v2_62\" ...\n9.728   rustc            911754 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atk-sys-0.18.2/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_30\", \"v2_32\", \"v2_34\", \"v2_38\", \"v2_46\", \"v2_50\")) -C metadata=c71e96213c395258 ...\n9.730   rustc            911758 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gdk-pixbuf-sys-0.18.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_40\", \"v2_42\")) -C metadata=d4fbec7ded70d8d5 ...\n9.733   rustc            911761 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cairo-sys-rs-0.18.2/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"glib\" --cfg feature=\"use_glib\" --check-cfg cfg(docsrs,test) ...\n9.735   rustc            911766 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pango-sys-0.18.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v1_42\", \"v1_44\", \"v1_46\", \"v1_48\", \"v1_50\", \"v1_52\")) -C metadata=95760bdc691fca0e ...\n9.739   rustc            911771 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gtk-sys-0.18.2/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v3_24\", \"v3_24_1\", \"v3_24_11\", \"v3_24_30\", \"v3_24_8\", \"v3_24_9\")) -C metadata=3e92667b2ec628fc ...\n9.746   rustc            911775 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/javascriptcore-rs-sys-1.1.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"v2_28\" --cfg feature=\"v2_38\" --check-cfg cfg(docsrs,test) ...\n9.747   rustc            911779 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/webkit2gtk-sys-2.0.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"v2_10\" --cfg feature=\"v2_12\" --cfg feature=\"v2_14\" ...\n9.751   rustc            911788 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/soup3-sys-0.5.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"v3_0\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v3_0\", \"v3_2\", \"v3_4\")) ...\n9.757   rustc            911792 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gdkx11-sys-0.18.2/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"cairo\", \"v3_24\", \"v3_24_2\")) -C metadata=ef98f6ac76597b4e ...\n9.769   rustc            911801 908551   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-2.0.17/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n9.780   cc               911818 911748   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/gobject-sys-f6b59444a30ac5fd/rustci1j3SE/symbols.o /target/debug/build/gobject-sys-f6b59444a30ac5fd/build_script_build-f6b59444a30ac5fd.build_script_build.d0d5cd41697241e1-cgu.0.r /target/debug/build/gobject-sys-f6b59444a30ac5fd/build_script_build-f6b59444a30ac5fd.1ejsowl0gjxgeidaw5k1o9icb.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.781   cc               911827 911818   0 /usr/bin/cc -m64 /target/debug/build/gobject-sys-f6b59444a30ac5fd/rustci1j3SE/symbols.o /target/debug/build/gobject-sys-f6b59444a30ac5fd/build_script_build-f6b59444a30ac5fd.build_script_build.d0d5cd41697241e1-cgu.0.r /target/debug/build/gobject-sys-f6b59444a30ac5fd/build_script_build-f6b59444a30ac5fd.1ejsowl0gjxgeidaw5k1o9icb.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.787   collect2         911836 911827   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdj9gLN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.789   cc               911829 911747   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/glib-sys-13eedc9ff3bf5907/rustcz0Cv7L/symbols.o /target/debug/build/glib-sys-13eedc9ff3bf5907/build_script_build-13eedc9ff3bf5907.build_script_build.6451c814820afebc-cgu.0.rcgu /target/debug/build/glib-sys-13eedc9ff3bf5907/build_script_build-13eedc9ff3bf5907.5r3gjxdpfb1oqx5yj5m1hiycg.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.791   cc               911844 911829   0 /usr/bin/cc -m64 /target/debug/build/glib-sys-13eedc9ff3bf5907/rustcz0Cv7L/symbols.o /target/debug/build/glib-sys-13eedc9ff3bf5907/build_script_build-13eedc9ff3bf5907.build_script_build.6451c814820afebc-cgu.0.rcgu /target/debug/build/glib-sys-13eedc9ff3bf5907/build_script_build-13eedc9ff3bf5907.5r3gjxdpfb1oqx5yj5m1hiycg.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.791   ld.lld           911845 911836   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdj9gLN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gobject-sys-f6b59444a30ac5fd/build_script_build-f6b59444a30ac5fd ...\n9.792   rust-lld         911845 911836   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdj9gLN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.794   cc               911846 911752   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/gio-sys-1684b809e16c705c/rustcqSHqbF/symbols.o /target/debug/build/gio-sys-1684b809e16c705c/build_script_build-1684b809e16c705c.build_script_build.a0581cef4741dae2-cgu.0.rcgu. /target/debug/build/gio-sys-1684b809e16c705c/build_script_build-1684b809e16c705c.8tzr4a6zzknzo0jtyu7yuqacq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.794   cc               911848 911846   0 /usr/bin/cc -m64 /target/debug/build/gio-sys-1684b809e16c705c/rustcqSHqbF/symbols.o /target/debug/build/gio-sys-1684b809e16c705c/build_script_build-1684b809e16c705c.build_script_build.a0581cef4741dae2-cgu.0.rcgu. /target/debug/build/gio-sys-1684b809e16c705c/build_script_build-1684b809e16c705c.8tzr4a6zzknzo0jtyu7yuqacq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.797   collect2         911849 911844   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRQ0cNp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.799   ld.lld           911854 911849   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRQ0cNp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/glib-sys-13eedc9ff3bf5907/build_script_build-13eedc9ff3bf5907 ...\n9.802   collect2         911855 911848   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccY8aKtv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.803   ld.lld           911861 911855   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccY8aKtv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gio-sys-1684b809e16c705c/build_script_build-1684b809e16c705c ...\n9.803   cc               911852 911758   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/gdk-pixbuf-sys-99ebdd3ff39c8a38/rustcejLWWf/symbols.o /target/debug/build/gdk-pixbuf-sys-99ebdd3ff39c8a38/build_script_build-99ebdd3ff39c8a38.build_script_build.575621406988ce8a-cgu. /target/debug/build/gdk-pixbuf-sys-99ebdd3ff39c8a38/build_script_build-99ebdd3ff39c8a38.0gc3kvsel0ddnoaovevnxq06g.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.804   rust-lld         911854 911849   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRQ0cNp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.804   cc               911860 911775   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/javascriptcore-rs-sys-ce8b621aa6c5c06b/rustc9z5Wn8/symbols.o /target/debug/build/javascriptcore-rs-sys-ce8b621aa6c5c06b/build_script_build-ce8b621aa6c5c06b.build_script_build.2fa4af6a5ed431 /target/debug/build/javascriptcore-rs-sys-ce8b621aa6c5c06b/build_script_build-ce8b621aa6c5c06b.215bhjjcgyw5qlx6j2a947tcu.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.805   rust-lld         911861 911855   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccY8aKtv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.805   cc               911862 911860   0 /usr/bin/cc -m64 /target/debug/build/javascriptcore-rs-sys-ce8b621aa6c5c06b/rustc9z5Wn8/symbols.o /target/debug/build/javascriptcore-rs-sys-ce8b621aa6c5c06b/build_script_build-ce8b621aa6c5c06b.build_script_build.2fa4af6a5ed431 /target/debug/build/javascriptcore-rs-sys-ce8b621aa6c5c06b/build_script_build-ce8b621aa6c5c06b.215bhjjcgyw5qlx6j2a947tcu.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.808   cc               911856 911779   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/webkit2gtk-sys-a2274efebb511770/rustc4pZ38n/symbols.o /target/debug/build/webkit2gtk-sys-a2274efebb511770/build_script_build-a2274efebb511770.build_script_build.1fd31a54239f2e4e-cgu. /target/debug/build/webkit2gtk-sys-a2274efebb511770/build_script_build-a2274efebb511770.9wvt76o3y6mlkcnqlh9ps0cwj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.808   cc               911863 911771   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/gtk-sys-1445a9c1b87c9ffd/rustcLF5MxP/symbols.o /target/debug/build/gtk-sys-1445a9c1b87c9ffd/build_script_build-1445a9c1b87c9ffd.build_script_build.6848d2929f0f347-cgu.0.rcgu.o /target/debug/build/gtk-sys-1445a9c1b87c9ffd/build_script_build-1445a9c1b87c9ffd.cykgw98lh10eaffzuurmnl430.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.809   cc               911864 911852   0 /usr/bin/cc -m64 /target/debug/build/gdk-pixbuf-sys-99ebdd3ff39c8a38/rustcejLWWf/symbols.o /target/debug/build/gdk-pixbuf-sys-99ebdd3ff39c8a38/build_script_build-99ebdd3ff39c8a38.build_script_build.575621406988ce8a-cgu. /target/debug/build/gdk-pixbuf-sys-99ebdd3ff39c8a38/build_script_build-99ebdd3ff39c8a38.0gc3kvsel0ddnoaovevnxq06g.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.809   cc               911867 911856   0 /usr/bin/cc -m64 /target/debug/build/webkit2gtk-sys-a2274efebb511770/rustc4pZ38n/symbols.o /target/debug/build/webkit2gtk-sys-a2274efebb511770/build_script_build-a2274efebb511770.build_script_build.1fd31a54239f2e4e-cgu. /target/debug/build/webkit2gtk-sys-a2274efebb511770/build_script_build-a2274efebb511770.9wvt76o3y6mlkcnqlh9ps0cwj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.810   cc               911868 911863   0 /usr/bin/cc -m64 /target/debug/build/gtk-sys-1445a9c1b87c9ffd/rustcLF5MxP/symbols.o /target/debug/build/gtk-sys-1445a9c1b87c9ffd/build_script_build-1445a9c1b87c9ffd.build_script_build.6848d2929f0f347-cgu.0.rcgu.o /target/debug/build/gtk-sys-1445a9c1b87c9ffd/build_script_build-1445a9c1b87c9ffd.cykgw98lh10eaffzuurmnl430.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.811   collect2         911870 911864   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccevTAIy.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.811   collect2         911866 911862   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRdw3Xo.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.812   collect2         911873 911867   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYTbluS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.812   ld.lld           911874 911870   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccevTAIy.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gdk-pixbuf-sys-99ebdd3ff39c8a38/build_script_build-99ebdd3ff39c8a38 ...\n9.813   cc               911869 911754   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/atk-sys-502a086b1a88df78/rustct8Qmor/symbols.o /target/debug/build/atk-sys-502a086b1a88df78/build_script_build-502a086b1a88df78.build_script_build.e0777fba1caca75b-cgu.0.rcgu. /target/debug/build/atk-sys-502a086b1a88df78/build_script_build-502a086b1a88df78.dwpbrm16i3lvcla693c2936s3.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.813   ld.lld           911877 911873   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYTbluS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/webkit2gtk-sys-a2274efebb511770/build_script_build-a2274efebb511770 ...\n9.814   ld.lld           911875 911866   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRdw3Xo.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/javascriptcore-rs-sys-ce8b621aa6c5c06b/build_script_build-ce8b621aa6c5c06b ...\n9.815   rust-lld         911875 911866   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRdw3Xo.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.816   cc               911878 911751   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/gdk-sys-f3a56defaf3a0eaf/rustcIbWzzU/symbols.o /target/debug/build/gdk-sys-f3a56defaf3a0eaf/build_script_build-f3a56defaf3a0eaf.build_script_build.a42b15eba3e5156e-cgu.0.rcgu. /target/debug/build/gdk-sys-f3a56defaf3a0eaf/build_script_build-f3a56defaf3a0eaf.7xwcczdwaqjhoji1lgnm2g4j7.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.816   cc               911879 911761   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/cairo-sys-rs-6cc82f16880d1516/rustcSo2kCJ/symbols.o /target/debug/build/cairo-sys-rs-6cc82f16880d1516/build_script_build-6cc82f16880d1516.build_script_build.d5684fed48f9187f-cgu.0. /target/debug/build/cairo-sys-rs-6cc82f16880d1516/build_script_build-6cc82f16880d1516.45mydky3bdut8e76j1f93kag5.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.817   cc               911883 911879   0 /usr/bin/cc -m64 /target/debug/build/cairo-sys-rs-6cc82f16880d1516/rustcSo2kCJ/symbols.o /target/debug/build/cairo-sys-rs-6cc82f16880d1516/build_script_build-6cc82f16880d1516.build_script_build.d5684fed48f9187f-cgu.0. /target/debug/build/cairo-sys-rs-6cc82f16880d1516/build_script_build-6cc82f16880d1516.45mydky3bdut8e76j1f93kag5.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.817   cc               911882 911878   0 /usr/bin/cc -m64 /target/debug/build/gdk-sys-f3a56defaf3a0eaf/rustcIbWzzU/symbols.o /target/debug/build/gdk-sys-f3a56defaf3a0eaf/build_script_build-f3a56defaf3a0eaf.build_script_build.a42b15eba3e5156e-cgu.0.rcgu. /target/debug/build/gdk-sys-f3a56defaf3a0eaf/build_script_build-f3a56defaf3a0eaf.7xwcczdwaqjhoji1lgnm2g4j7.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.817   rust-lld         911877 911873   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYTbluS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.817   collect2         911885 911868   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccsmJftb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.819   cc               911880 911869   0 /usr/bin/cc -m64 /target/debug/build/atk-sys-502a086b1a88df78/rustct8Qmor/symbols.o /target/debug/build/atk-sys-502a086b1a88df78/build_script_build-502a086b1a88df78.build_script_build.e0777fba1caca75b-cgu.0.rcgu. /target/debug/build/atk-sys-502a086b1a88df78/build_script_build-502a086b1a88df78.dwpbrm16i3lvcla693c2936s3.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.821   collect2         911903 911882   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjQeh8H.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.821   ld.lld           911901 911885   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccsmJftb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gtk-sys-1445a9c1b87c9ffd/build_script_build-1445a9c1b87c9ffd ...\n9.821   cc               911881 911766   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/pango-sys-36f28451941192e1/rustcxI1Paf/symbols.o /target/debug/build/pango-sys-36f28451941192e1/build_script_build-36f28451941192e1.build_script_build.d9a5aede8f97695c-cgu.0.rcg /target/debug/build/pango-sys-36f28451941192e1/build_script_build-36f28451941192e1.8nn9rl2xnlpb96kn2sj9djk4q.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.821   collect2         911902 911883   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbdaX6D.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.821   rust-lld         911874 911870   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccevTAIy.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.822   cc               911904 911881   0 /usr/bin/cc -m64 /target/debug/build/pango-sys-36f28451941192e1/rustcxI1Paf/symbols.o /target/debug/build/pango-sys-36f28451941192e1/build_script_build-36f28451941192e1.build_script_build.d9a5aede8f97695c-cgu.0.rcg /target/debug/build/pango-sys-36f28451941192e1/build_script_build-36f28451941192e1.8nn9rl2xnlpb96kn2sj9djk4q.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.822   ld.lld           911905 911903   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjQeh8H.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gdk-sys-f3a56defaf3a0eaf/build_script_build-f3a56defaf3a0eaf ...\n9.823   ld.lld           911906 911902   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbdaX6D.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/cairo-sys-rs-6cc82f16880d1516/build_script_build-6cc82f16880d1516 ...\n9.823   rust-lld         911901 911885   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccsmJftb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.824   rust-lld         911906 911902   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbdaX6D.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.825   collect2         911908 911904   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYp2r12.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.826   ld.lld           911910 911908   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYp2r12.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/pango-sys-36f28451941192e1/build_script_build-36f28451941192e1 ...\n9.828   rust-lld         911910 911908   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYp2r12.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.829   cc               911911 911792   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/gdkx11-sys-22d82cfc3eab7e16/rustcQ47B2S/symbols.o /target/debug/build/gdkx11-sys-22d82cfc3eab7e16/build_script_build-22d82cfc3eab7e16.build_script_build.6c555fbe42f1d7cc-cgu.0.rc /target/debug/build/gdkx11-sys-22d82cfc3eab7e16/build_script_build-22d82cfc3eab7e16.5jquqezoauzbkufumiqz4v4ub.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.830   rust-lld         911905 911903   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjQeh8H.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.830   collect2         911907 911880   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccV2rUvj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.833   cc               911909 911788   0 /tmp/native-trace-907906-1783998323002/shims/cc -m64 /target/debug/build/soup3-sys-49050de6244188ec/rustc8cGpDI/symbols.o /target/debug/build/soup3-sys-49050de6244188ec/build_script_build-49050de6244188ec.build_script_build.54104c911d6b3057-cgu.0.rcg /target/debug/build/soup3-sys-49050de6244188ec/build_script_build-49050de6244188ec.b2eyhow29j9z2uu5qju0hocd0.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.833   cc               911912 911911   0 /usr/bin/cc -m64 /target/debug/build/gdkx11-sys-22d82cfc3eab7e16/rustcQ47B2S/symbols.o /target/debug/build/gdkx11-sys-22d82cfc3eab7e16/build_script_build-22d82cfc3eab7e16.build_script_build.6c555fbe42f1d7cc-cgu.0.rc /target/debug/build/gdkx11-sys-22d82cfc3eab7e16/build_script_build-22d82cfc3eab7e16.5jquqezoauzbkufumiqz4v4ub.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.834   cc               911915 911909   0 /usr/bin/cc -m64 /target/debug/build/soup3-sys-49050de6244188ec/rustc8cGpDI/symbols.o /target/debug/build/soup3-sys-49050de6244188ec/build_script_build-49050de6244188ec.build_script_build.54104c911d6b3057-cgu.0.rcg /target/debug/build/soup3-sys-49050de6244188ec/build_script_build-49050de6244188ec.b2eyhow29j9z2uu5qju0hocd0.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-ee6a2c70e7015b36.rlib /target/debug/deps/libversion_compare-338263f8f7c271f5.rlib /target/debug/deps/libpkg_config-d058549e4bf596c7.rlib /target/debug/deps/libcfg_expr-b3e4385ea58cb7c5.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-c85e941a8f6330c7.rlib /target/debug/deps/libtoml-742cbbb7353bb4f6.rlib /target/debug/deps/libtoml_edit-93a28c8d20af731a.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-23f16fea0fe6eab7.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-7c65cc4648dc580d.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n9.835   ld.lld           911913 911907   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccV2rUvj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/atk-sys-502a086b1a88df78/build_script_build-502a086b1a88df78 ...\n9.836   collect2         911931 911912   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cctBZT6a.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.838   rust-lld         911913 911907   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccV2rUvj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.838   collect2         911932 911915   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7RWLho.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.840   ld.lld           911933 911931   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cctBZT6a.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gdkx11-sys-22d82cfc3eab7e16/build_script_build-22d82cfc3eab7e16 ...\n9.840   ld.lld           911934 911932   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7RWLho.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/soup3-sys-49050de6244188ec/build_script_build-49050de6244188ec ...\n9.843   rust-lld         911933 911931   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cctBZT6a.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.843   rust-lld         911934 911932   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7RWLho.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n10.095  build-script-bu  912117 908551   0 /target/debug/build/glib-sys-13eedc9ff3bf5907/build-script-build\n10.098  pkg-config       912120 912117   0 /tmp/native-trace-907906-1783998323002/shims/pkg-config --libs --cflags glib-2.0 glib-2.0 >= 2.70\n10.098  pkg-config       912121 912120   0 /usr/bin/pkg-config --libs --cflags glib-2.0 glib-2.0 >= 2.70\n10.099  build-script-bu  912119 908551   0 /target/debug/build/gobject-sys-f6b59444a30ac5fd/build-script-build\n10.102  pkg-config       912123 912119   0 /tmp/native-trace-907906-1783998323002/shims/pkg-config --libs --cflags gobject-2.0 gobject-2.0 >= 2.70\n10.103  pkg-config       912125 912123   0 /usr/bin/pkg-config --libs --cflags gobject-2.0 gobject-2.0 >= 2.70\n10.105  build-script-bu  912124 908551   0 /target/debug/build/cairo-sys-rs-6cc82f16880d1516/build-script-build\n10.108  pkg-config       912126 912124   0 /tmp/native-trace-907906-1783998323002/shims/pkg-config --libs --cflags cairo cairo >= 1.14\n10.109  pkg-config       912127 912126   0 /usr/bin/pkg-config --libs --cflags cairo cairo >= 1.14\n10.764  16               912155 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n10.775  cc               912156 911120   0 /tmp/native-trace-907723-1783998322683/shims/cc -Wl,--version-script=/target/debug/deps/rustcNu352o/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcNu352o/symbols.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.00.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.01.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.02.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.03.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.04.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.05.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.06.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.07.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.08.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.09.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.10.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.11.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.12.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.13.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.14.rcgu.o ...\n10.776  frpc             912155 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n10.776  cc               912158 912156   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcNu352o/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcNu352o/symbols.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.00.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.01.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.02.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.03.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.04.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.05.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.06.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.07.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.08.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.09.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.10.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.11.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.12.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.13.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.14.rcgu.o ...\n10.779  collect2         912165 912158   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDQtDjk.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libglib_macros-7780edfb62714916.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcNu352o/raw-dylibs ...\n10.780  ld.lld           912166 912165   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDQtDjk.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libglib_macros-7780edfb62714916.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcNu352o/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n10.781  rust-lld         912166 912165   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDQtDjk.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libglib_macros-7780edfb62714916.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n11.068  cc               912196 911647   0 /tmp/native-trace-907906-1783998323002/shims/cc -Wl,--version-script=/target/debug/deps/rustc1ECWOY/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc1ECWOY/symbols.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.00.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.01.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.02.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.03.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.04.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.05.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.06.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.07.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.08.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.09.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.10.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.11.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.12.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.13.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.14.rcgu.o ...\n11.069  cc               912197 912196   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc1ECWOY/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc1ECWOY/symbols.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.00.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.01.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.02.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.03.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.04.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.05.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.06.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.07.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.08.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.09.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.10.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.11.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.12.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.13.rcgu.o /target/debug/deps/glib_macros-7780edfb62714916.glib_macros.826beedc4af1b175-cgu.14.rcgu.o ...\n11.072  collect2         912198 912197   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnVVcXE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libglib_macros-7780edfb62714916.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc1ECWOY/raw-dylibs ...\n11.073  ld.lld           912199 912198   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnVVcXE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libglib_macros-7780edfb62714916.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc1ECWOY/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n11.074  rust-lld         912199 912198   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnVVcXE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libglib_macros-7780edfb62714916.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n15.691  runc             912216 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2046224714 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n15.697  exe              912224 912216   0 /proc/self/exe init\n15.728  curl             912226 912216   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n"
    },
    {
      "argv": [
        "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 907979,
      "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build-script-build",
      "pid": 907979,
      "ppid": 907920,
      "root_cargo_pid": 907920,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "duktape",
        "-Wall",
        "-Wextra",
        "-std=c99",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/duktape.o",
        "-c",
        "duktape/duktape.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 907979,
      "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 907980,
      "ppid": 907979,
      "root_cargo_pid": 907920,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "duktape",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "duktape/duktape.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "duktape.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/duktape.o",
        "-g",
        "-O0",
        "-Wall",
        "-Wextra",
        "-std=c99",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 907979,
      "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 907982,
      "ppid": 907980,
      "root_cargo_pid": 907920,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "duktape",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/duktape.o",
        "/tmp/ccsknfZl.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 907979,
      "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 909640,
      "ppid": 907980,
      "root_cargo_pid": 907920,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "duktape",
        "-Wall",
        "-Wextra",
        "-std=c99",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/wrapper.o",
        "-c",
        "duktape/wrapper.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 907979,
      "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 909769,
      "ppid": 907979,
      "root_cargo_pid": 907920,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "duktape",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "duktape/wrapper.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "wrapper.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/wrapper.o",
        "-g",
        "-O0",
        "-Wall",
        "-Wextra",
        "-std=c99",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 907979,
      "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 909772,
      "ppid": 909769,
      "root_cargo_pid": 907920,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "duktape",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/wrapper.o",
        "/tmp/cc4Y5utF.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 907979,
      "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 909802,
      "ppid": 909769,
      "root_cargo_pid": 907920,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "crs",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/libduktape.a",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/duktape.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/wrapper.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 907979,
      "build_script_target_dir": "ducc-sys-cc5bc5d8537a5ab0",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 909808,
      "ppid": 907979,
      "root_cargo_pid": 907920,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "ducc-sys",
      "cwd": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "event_id": "bsrun:a1ba2fddb0656455:e9794bf2d1e8e296:c38049f959723422",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
      "out_dir": "/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
      "success": true,
      "target": null,
      "version": "0.1.2",
      "_owner": {
        "crate": "ducc-sys",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2#ducc-sys@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2",
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
