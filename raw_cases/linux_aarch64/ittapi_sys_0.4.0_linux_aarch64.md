# `ittapi-sys` `0.4.0`

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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
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
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh",
    "/target/debug/build/ittapi-sys-153a64372a747f59",
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
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.00.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.02.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.03.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.04.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.05.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.06.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.07.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.08.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.09.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.10.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.11.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.01.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.12.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.13.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.14.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.15.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib(find_msvc_tools-60e3732174de9068.find_msvc_tools.ede48c3253d6796d-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib(find_msvc_tools-60e3732174de9068.find_msvc_tools.ede48c3253d6796d-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib(shlex-f2fa52250b1d670f.shlex.352c8e657ac65ae8-cgu.0.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-535156-1783994714120676298.map",
  "pid": 535156,
  "ppid": 535100,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-535156-1783994714120676298.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/libittnotify.a`

Owner: `ittapi-sys` `0.4.0`

### Source files

* `/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0/c-library/src/ittnotify/ittnotify_static.c`
* `/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0/c-library/src/ittnotify/jitprofiling.c`

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
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-Wall",
    "-Wextra",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "-c",
    "c-library/src/ittnotify/ittnotify_static.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 535282,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 535292,
  "ppid": 535282,
  "root_cargo_pid": 533330,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
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
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-Wall",
    "-Wextra",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-jitprofiling.o",
    "-c",
    "c-library/src/ittnotify/jitprofiling.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 535282,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 535416,
  "ppid": 535282,
  "root_cargo_pid": 533330,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
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
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-imultiarch",
    "aarch64-linux-gnu",
    "c-library/src/ittnotify/ittnotify_static.c",
    "-quiet",
    "-dumpbase",
    "ittnotify_static.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "..."
  ],
  "src": "c-library/src/ittnotify/ittnotify_static.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-ittnotify_static.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 535296,
  "ppid": 535292,
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "root_cargo_pid": 533330,
  "build_script_root_pid": 535282,
  "build_script_related": true,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
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
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-imultiarch",
    "aarch64-linux-gnu",
    "c-library/src/ittnotify/jitprofiling.c",
    "-quiet",
    "-dumpbase",
    "jitprofiling.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-jitprofiling.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "..."
  ],
  "src": "c-library/src/ittnotify/jitprofiling.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-jitprofiling.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 535419,
  "ppid": 535416,
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "root_cargo_pid": 533330,
  "build_script_root_pid": 535282,
  "build_script_related": true,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
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
    "cqD",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/libittnotify.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-jitprofiling.o"
  ],
  "archive": "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/libittnotify.a",
  "objects": [
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-jitprofiling.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 535440,
  "ppid": 535282,
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "root_cargo_pid": 533330,
  "build_script_root_pid": 535282,
  "build_script_related": true,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
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
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "workspace_root": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.4",
      "name": "aho-corasick",
      "version": "1.1.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bindgen@0.68.1",
      "name": "bindgen",
      "version": "0.68.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bindgen-0.68.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bindgen-0.68.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.13.0",
      "name": "bitflags",
      "version": "2.13.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.13.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.13.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
      "name": "cc",
      "version": "1.2.67",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cexpr@0.6.0",
      "name": "cexpr",
      "version": "0.6.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cexpr-0.6.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cexpr-0.6.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.4",
      "name": "cfg-if",
      "version": "1.0.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#clang-sys@1.8.1",
      "name": "clang-sys",
      "version": "1.8.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clang-sys-1.8.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clang-sys-1.8.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#diff@0.1.13",
      "name": "diff",
      "version": "0.1.13",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/diff-0.1.13/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/diff-0.1.13"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.16.0",
      "name": "either",
      "version": "1.16.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.14",
      "name": "errno",
      "version": "0.3.14",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.14/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.14"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
      "name": "find-msvc-tools",
      "version": "0.1.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#glob@0.3.3",
      "name": "glob",
      "version": "0.3.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#home@0.5.12",
      "name": "home",
      "version": "0.5.12",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/home-0.5.12/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/home-0.5.12"
    },
    {
      "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
      "name": "ittapi-sys",
      "version": "0.4.0",
      "manifest_path": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.5.0",
      "name": "lazy_static",
      "version": "1.5.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazycell@1.3.0",
      "name": "lazycell",
      "version": "1.3.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazycell-1.3.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazycell-1.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
      "name": "libc",
      "version": "0.2.186",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libloading@0.8.9",
      "name": "libloading",
      "version": "0.8.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.8.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.8.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.4.15",
      "name": "linux-raw-sys",
      "version": "0.4.15",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.15/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.15"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.33",
      "name": "log",
      "version": "0.4.33",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.33/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.33"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
      "name": "memchr",
      "version": "2.8.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#minimal-lexical@0.2.1",
      "name": "minimal-lexical",
      "version": "0.2.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/minimal-lexical-0.2.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/minimal-lexical-0.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#nom@7.1.3",
      "name": "nom",
      "version": "7.1.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/nom-7.1.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/nom-7.1.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.21.4",
      "name": "once_cell",
      "version": "1.21.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#peeking_take_while@0.1.2",
      "name": "peeking_take_while",
      "version": "0.1.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/peeking_take_while-0.1.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/peeking_take_while-0.1.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#prettyplease@0.2.37",
      "name": "prettyplease",
      "version": "0.2.37",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prettyplease-0.2.37/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prettyplease-0.2.37"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
      "name": "proc-macro2",
      "version": "1.0.106",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
      "name": "quote",
      "version": "1.0.46",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.13.0",
      "name": "regex",
      "version": "1.13.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.15",
      "name": "regex-automata",
      "version": "0.4.15",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.11",
      "name": "regex-syntax",
      "version": "0.8.11",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustc-hash@1.1.0",
      "name": "rustc-hash",
      "version": "1.1.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc-hash-1.1.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc-hash-1.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@0.38.44",
      "name": "rustix",
      "version": "0.38.44",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.44/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.44"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@1.3.0",
      "name": "shlex",
      "version": "1.3.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
      "name": "shlex",
      "version": "2.0.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
      "name": "syn",
      "version": "2.0.118",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
      "name": "unicode-ident",
      "version": "1.0.24",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#which@4.4.2",
      "name": "which",
      "version": "4.4.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/which-4.4.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/which-4.4.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.1",
      "name": "windows-link",
      "version": "0.2.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.59.0",
      "name": "windows-sys",
      "version": "0.59.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.59.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.59.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.61.2",
      "name": "windows-sys",
      "version": "0.61.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.52.6",
      "name": "windows-targets",
      "version": "0.52.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.52.6",
      "name": "windows_aarch64_gnullvm",
      "version": "0.52.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.52.6",
      "name": "windows_aarch64_msvc",
      "version": "0.52.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.52.6",
      "name": "windows_i686_gnu",
      "version": "0.52.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnullvm@0.52.6",
      "name": "windows_i686_gnullvm",
      "version": "0.52.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnullvm-0.52.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnullvm-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.52.6",
      "name": "windows_i686_msvc",
      "version": "0.52.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.52.6",
      "name": "windows_x86_64_gnu",
      "version": "0.52.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.52.6",
      "name": "windows_x86_64_gnullvm",
      "version": "0.52.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
      "name": "windows_x86_64_msvc",
      "version": "0.52.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6"
    }
  ],
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 535156,
  "ppid": 535100,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ittapi-sys",
  "cargo_pkg_version": "0.4.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "event_id": "used:cc:bc9fe02df21f3b54:dc3d20b22f9d305e:31a657552161aa04",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "path": "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
  "pid": 535156,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ittapi-sys",
  "cargo_pkg_version": "0.4.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "event_id": "used:cc:bc9fe02df21f3b54:fddc94802acd2bb7:31a657552161aa04",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
  "pid": 535156,
  "sha256": "f9eb66f132263251a2124a29e191966e7ba8055f629d1529645d5625bf796841",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ittapi-sys",
  "cargo_pkg_version": "0.4.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "event_id": "used:cc:bc9fe02df21f3b54:46055e5a431f99a9:31a657552161aa04",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
  "pid": 535156,
  "sha256": "8e17595a9fb41c47002abc8974f86269619bbec870550d21bd3e6601f505f063",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ittapi-sys",
  "cargo_pkg_version": "0.4.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "event_id": "used:cc:bc9fe02df21f3b54:3dcff77cb2bb205f:31a657552161aa04",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
  "pid": 535156,
  "sha256": "a48ea15d88c4623620e8c89598dd5c14b048119c024940d5455523808f0983ba",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ittapi-sys",
  "cargo_pkg_version": "0.4.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "event_id": "used:cc:bc9fe02df21f3b54:241464f73c6bfda6:31a657552161aa04",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
  "pid": 535156,
  "sha256": "c4491feae63d4722dc324571546e79c99482db08a0d6e76fb800acca485e9a94",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ittapi-sys",
  "cargo_pkg_version": "0.4.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "event_id": "used:cc:bc9fe02df21f3b54:de7f33f6a78acc8e:31a657552161aa04",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
  "pid": 535156,
  "sha256": "6dcfbe0cae6dab2cf5caf5c73e28f49315af237b002de957a58be687ab96448e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ittapi-sys",
  "cargo_pkg_version": "0.4.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "event_id": "used:cc:bc9fe02df21f3b54:5e81f3534cb5bf33:31a657552161aa04",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
  "pid": 535156,
  "sha256": "0e8c91e8502317498de977ac4fbe63e831b73f34cff11f8fe2ddafac42ea9f70",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ittapi-sys",
  "cargo_pkg_version": "0.4.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "event_id": "used:cc:bc9fe02df21f3b54:7f47abafd628d4ac:31a657552161aa04",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
  "pid": 535156,
  "sha256": "bfb00a1de9735fc70400b20a02c74907ea8edcc00dfa2a4a6afb00027658c6d4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ittapi-sys",
  "cargo_pkg_version": "0.4.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "event_id": "used:cc:bc9fe02df21f3b54:083624c412ad3e09:31a657552161aa04",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
  "pid": 535156,
  "sha256": "1e390e913e72f311b71a16e85e7be1d7349e44c86eb4706b911c279b20009c87",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ittapi-sys",
  "cargo_pkg_version": "0.4.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "event_id": "used:cc:bc9fe02df21f3b54:7b16ea71232f9d6e:31a657552161aa04",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
  "pid": 535156,
  "sha256": "b2899e985ec507a1cde58b4b2ccdd03eb8bf1259c32af93fa2e51adb7dc6beca",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
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
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "cargo_pkg_name": "ittapi-sys",
  "cargo_pkg_version": "0.4.0",
  "context_path": "/tmp/native-trace-531044-1783994705589/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-531044-1783994705589/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 535156,
  "ppid": 535100,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh",
    "/target/debug/build/ittapi-sys-153a64372a747f59",
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
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.00.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.02.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.03.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.04.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.05.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.06.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.07.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.08.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.09.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.10.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.11.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.01.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.12.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.13.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.14.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.15.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib(find_msvc_tools-60e3732174de9068.find_msvc_tools.ede48c3253d6796d-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib(find_msvc_tools-60e3732174de9068.find_msvc_tools.ede48c3253d6796d-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib(shlex-f2fa52250b1d670f.shlex.352c8e657ac65ae8-cgu.0.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-535156-1783994714120676298.map",
  "pid": 535156,
  "ppid": 535100,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-535156-1783994714120676298.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
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
  "parse_error_count": 2,
  "parsed_event_count": 943,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 945,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": " ...\n17.270  collect2         538327 538325   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc49pQSP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcwrY8aa/raw-dylibs ...\n17.274  ld.lld           538328 538327   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc49pQSP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcwrY8aa/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n17.279  rust-lld         538328 538327   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc49pQSP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n17.282  rustc            538333 527474   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_protocols --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-protocols-0.31.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client\" --cfg feature=\"staging\" --cfg feature=\"unstable\" ...\n17.298  rustc            538335 527474   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_cursor --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-cursor-0.31.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=62be080b652e5042 ...\n17.304  rustc            538336 527474   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name calloop_wayland_source --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/calloop-wayland-source-0.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"log\")) -C metadata=17458c302e9afa03 ...\n17.496  rustc            538373 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-1.0.56/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n17.708  rustc            538385 532681   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde_derive --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.219/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n17.709  rustc            538389 532681   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n17.711  rustc            538390 532681   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clap_derive --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_derive-4.5.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::verbose_file_reads --warn=unused_qualifications ...\n17.712  rustc            538391 532681   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name arg_enum_proc_macro --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/arg_enum_proc_macro-0.3.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n18.360  cc               538439 538391   0 /tmp/native-trace-530685-1783994704613/shims/cc -Wl,--version-script=/target/debug/deps/rustc8wmOmz/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc8wmOmz/symbols.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.0.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.1.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.2.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.3.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.4.rcgu.o /target/debug/deps/rustc8wmOmz/rmeta.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.58q2ufzvuc8xaydmt1rvqk5d2.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-857859587c15809d.rlib /target/debug/deps/libquote-840405f79b9ea204.rlib /target/debug/deps/libproc_macro2-64766898606113cc.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- ...\n18.367  cc               538440 538439   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc8wmOmz/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc8wmOmz/symbols.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.0.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.1.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.2.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.3.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.4.rcgu.o /target/debug/deps/rustc8wmOmz/rmeta.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.58q2ufzvuc8xaydmt1rvqk5d2.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-857859587c15809d.rlib /target/debug/deps/libquote-840405f79b9ea204.rlib /target/debug/deps/libproc_macro2-64766898606113cc.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- ...\n18.373  collect2         538441 538440   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6Apxzu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc8wmOmz/raw-dylibs ...\n18.378  ld.lld           538442 538441   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6Apxzu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc8wmOmz/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.381  rust-lld         538442 538441   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6Apxzu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n18.455  runc             538461 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process2251340981 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n18.476  exe              538470 538461   0 \n18.521  etcdctl          538473 538461   0 /usr/local/bin/etcdctl endpoint health\n18.623  rustc            538495 533138   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde_derive --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.219/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n18.627  rustc            538494 533138   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n18.627  rustc            538497 533138   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clap_derive --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_derive-4.5.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::verbose_file_reads --warn=unused_qualifications ...\n18.631  cc               538498 538268   0 /tmp/native-trace-529391-1783994701958/shims/cc -Wl,--version-script=/target/debug/deps/rustcZG87GP/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcZG87GP/symbols.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.14.rcgu.o ...\n18.636  cc               538499 538498   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcZG87GP/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcZG87GP/symbols.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.14.rcgu.o ...\n18.649  rustc            538496 533138   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name arg_enum_proc_macro --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/arg_enum_proc_macro-0.3.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n18.656  collect2         538507 538499   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccx9WR7V.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcZG87GP/raw-dylibs ...\n18.661  ld.lld           538508 538507   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccx9WR7V.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcZG87GP/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.666  rust-lld         538508 538507   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccx9WR7V.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n19.048  rustc            538553 531131   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n19.241  cc               538583 538373   0 /tmp/native-trace-529392-1783994701964/shims/cc -Wl,--version-script=/target/debug/deps/rustcZYqEkq/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcZYqEkq/symbols.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.14.rcgu.o ...\n19.244  cc               538584 538583   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcZYqEkq/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcZYqEkq/symbols.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.14.rcgu.o ...\n19.248  collect2         538585 538584   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjOfd9p.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-f3801be1b6b47087.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcZYqEkq/raw-dylibs ...\n19.257  ld.lld           538586 538585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjOfd9p.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-f3801be1b6b47087.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcZYqEkq/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n19.265  rust-lld         538586 538585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjOfd9p.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-f3801be1b6b47087.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n19.273  cc               538587 538496   0 /tmp/native-trace-530944-1783994705241/shims/cc -Wl,--version-script=/target/debug/deps/rustcxTGTrN/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcxTGTrN/symbols.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.0.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.1.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.2.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.3.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.4.rcgu.o /target/debug/deps/rustcxTGTrN/rmeta.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.58q2ufzvuc8xaydmt1rvqk5d2.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-857859587c15809d.rlib /target/debug/deps/libquote-840405f79b9ea204.rlib /target/debug/deps/libproc_macro2-64766898606113cc.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- ...\n19.281  cc               538590 538587   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcxTGTrN/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcxTGTrN/symbols.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.0.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.1.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.2.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.3.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.4.rcgu.o /target/debug/deps/rustcxTGTrN/rmeta.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.58q2ufzvuc8xaydmt1rvqk5d2.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-857859587c15809d.rlib /target/debug/deps/libquote-840405f79b9ea204.rlib /target/debug/deps/libproc_macro2-64766898606113cc.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- ...\n19.282  collect2         538591 538590   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cchZzgln.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcxTGTrN/raw-dylibs ...\n19.293  ld.lld           538592 538591   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cchZzgln.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcxTGTrN/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n19.300  rust-lld         538592 538591   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cchZzgln.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n19.681  rustc            538648 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.56/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=6861f6d9a519659f ...\n19.836  cc               538664 538267   0 /tmp/native-trace-529391-1783994701958/shims/cc -Wl,--version-script=/target/debug/deps/rustcOskmb5/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcOskmb5/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n19.839  cc               538665 538664   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcOskmb5/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcOskmb5/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n19.844  collect2         538666 538665   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczyQapw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcOskmb5/raw-dylibs ...\n19.849  ld.lld           538667 538666   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczyQapw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcOskmb5/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n19.856  rust-lld         538667 538666   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczyQapw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n20.064  rustc            538697 523706   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name sctk_adwaita --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/sctk-adwaita-0.8.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"ab_glyph\" --cfg feature=\"memmap2\" --check-cfg cfg(docsrs,test) ...\n20.221  rustc            538717 531131   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clap --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.5.38/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::verbose_file_reads --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes ...\n20.442  cc               538745 538389   0 /tmp/native-trace-530685-1783994704613/shims/cc -Wl,--version-script=/target/debug/deps/rustc0RqHuC/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc0RqHuC/symbols.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.14.rcgu.o ...\n20.446  cc               538747 538745   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc0RqHuC/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc0RqHuC/symbols.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.14.rcgu.o ...\n20.461  collect2         538751 538747   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc30WuH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc0RqHuC/raw-dylibs ...\n20.466  ld.lld           538752 538751   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc30WuH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc0RqHuC/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n20.472  rust-lld         538752 538751   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc30WuH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n20.891  cc               538810 538494   0 /tmp/native-trace-530944-1783994705241/shims/cc -Wl,--version-script=/target/debug/deps/rustcCqsGXw/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcCqsGXw/symbols.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.14.rcgu.o ...\n20.894  cc               538809 538390   0 /tmp/native-trace-530685-1783994704613/shims/cc -Wl,--version-script=/target/debug/deps/rustckRDdof/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustckRDdof/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n20.900  cc               538812 538810   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcCqsGXw/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcCqsGXw/symbols.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.14.rcgu.o ...\n20.908  cc               538814 538809   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustckRDdof/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustckRDdof/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n20.914  collect2         538816 538812   0 \n20.916  ld.lld           538817 538816   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMG89yd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcCqsGXw/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n20.921  rust-lld         538817 538816   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMG89yd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n20.924  collect2         538815 538814   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnz8fQO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustckRDdof/raw-dylibs ...\n20.926  ld.lld           538818 538815   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnz8fQO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustckRDdof/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n20.928  rust-lld         538818 538815   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnz8fQO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n20.952  rustc            538821 532681   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n21.071  rustc            538867 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name polling --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/polling-3.4.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=18f523713bb5ba7f ...\n21.083  rustc            538869 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_backend --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-backend-0.3.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client_system\" --cfg feature=\"dlopen\" --check-cfg cfg(docsrs,test) ...\n21.269  16               538888 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n21.297  frpc             538888 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n21.307  rustc            538891 532681   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clap --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.5.38/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::verbose_file_reads --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes ...\n21.363  rustc            538909 533138   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n21.386  cc               538911 538497   0 /tmp/native-trace-530944-1783994705241/shims/cc -Wl,--version-script=/target/debug/deps/rustchZFaOr/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustchZFaOr/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n21.407  cc               538917 538911   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustchZFaOr/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustchZFaOr/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n21.412  collect2         538918 538917   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdaDYl3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustchZFaOr/raw-dylibs ...\n21.418  ld.lld           538919 538918   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdaDYl3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustchZFaOr/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n21.421  rust-lld         538919 538918   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdaDYl3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n21.539  rustc            538945 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name calloop --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/calloop-0.12.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"async-task\", \"block_on\", \"executor\", \"futures-io\", \"nightly_coverage\", \"nix\", \"pin-utils\", \"signals\")) -C metadata=74e7b5e683cc762c ...\n21.654  cc               538961 538262   0 /tmp/native-trace-529391-1783994701958/shims/cc -Wl,--version-script=/target/debug/deps/rustctLgo6T/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustctLgo6T/symbols.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.00.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.01.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.02.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.03.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.04.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.05.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.06.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.07.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.08.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.09.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.10.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.11.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.12.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.13.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.14.rcgu.o ...\n21.657  cc               538965 538961   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustctLgo6T/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustctLgo6T/symbols.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.00.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.01.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.02.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.03.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.04.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.05.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.06.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.07.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.08.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.09.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.10.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.11.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.12.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.13.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.14.rcgu.o ...\n21.661  collect2         538966 538965   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm6aUee.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustctLgo6T/raw-dylibs ...\n21.665  ld.lld           538967 538966   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm6aUee.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustctLgo6T/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n21.669  rust-lld         538967 538966   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm6aUee.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n21.743  rustc            538989 533138   0 \n21.854  rustc            539008 527474   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_protocols_wlr --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-protocols-wlr-0.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client\" --cfg feature=\"wayland-client\" --check-cfg cfg(docsrs,test) ...\n21.857  rustc            539007 527474   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_protocols_plasma --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-protocols-plasma-0.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client\" --cfg feature=\"wayland-client\" --check-cfg cfg(docsrs,test) ...\n21.947  rustc            539023 523706   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name winit --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"ahash\" --cfg feature=\"bytemuck\" --cfg feature=\"default\" ...\n22.026  rustc            539034 531131   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.219/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive\" --cfg feature=\"serde_derive\" ...\n"
}
```

#### Record 18

```json
{
  "argv": [
    "/target/debug/build/ittapi-sys-153a64372a747f59/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 535282,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/ittapi-sys-153a64372a747f59/build-script-build",
  "pid": 535282,
  "ppid": 533330,
  "root_cargo_pid": 533330,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out"
}
```

#### Record 19

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-E",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/11740837994362044329detect_compiler_family.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 535282,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 535283,
  "ppid": 535282,
  "root_cargo_pid": 533330,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 20

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-quiet",
    "-imultiarch",
    "aarch64-linux-gnu",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/11740837994362044329detect_compiler_family.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 535282,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 535284,
  "ppid": 535283,
  "root_cargo_pid": 533330,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 21

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 535282,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 535291,
  "ppid": 535282,
  "root_cargo_pid": 533330,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_cwd_recovered_from_build_script_run": true
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
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-Wall",
    "-Wextra",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "-c",
    "c-library/src/ittnotify/ittnotify_static.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 535282,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 535292,
  "ppid": 535282,
  "root_cargo_pid": 533330,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
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
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-imultiarch",
    "aarch64-linux-gnu",
    "c-library/src/ittnotify/ittnotify_static.c",
    "-quiet",
    "-dumpbase",
    "ittnotify_static.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 535282,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 535296,
  "ppid": 535292,
  "root_cargo_pid": 533330,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 24

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-I",
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "/tmp/ccardtFs.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 535282,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 535393,
  "ppid": 535292,
  "root_cargo_pid": 533330,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 25

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-Wall",
    "-Wextra",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-jitprofiling.o",
    "-c",
    "c-library/src/ittnotify/jitprofiling.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 535282,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 535416,
  "ppid": 535282,
  "root_cargo_pid": 533330,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 26

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-imultiarch",
    "aarch64-linux-gnu",
    "c-library/src/ittnotify/jitprofiling.c",
    "-quiet",
    "-dumpbase",
    "jitprofiling.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-jitprofiling.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 535282,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 535419,
  "ppid": 535416,
  "root_cargo_pid": 533330,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 27

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-I",
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-jitprofiling.o",
    "/tmp/ccmxA7lO.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 535282,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 535431,
  "ppid": 535416,
  "root_cargo_pid": 533330,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 28

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cqD",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/libittnotify.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-jitprofiling.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 535282,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 535440,
  "ppid": 535282,
  "root_cargo_pid": 533330,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 29

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "sD",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/libittnotify.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 535282,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 535443,
  "ppid": 535282,
  "root_cargo_pid": 533330,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 30

```json
{
  "crate": "ittapi-sys",
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "event_id": "bsrun:e7bbd0aa31554544:cda8081d828c41f0:f2ef5110e3cd48e0",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/ittapi-sys-153a64372a747f59/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
  "success": true,
  "target": null,
  "version": "0.4.0",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  }
}
```

#### Record 31

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-imultiarch",
    "aarch64-linux-gnu",
    "c-library/src/ittnotify/ittnotify_static.c",
    "-quiet",
    "-dumpbase",
    "ittnotify_static.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "..."
  ],
  "src": "c-library/src/ittnotify/ittnotify_static.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-ittnotify_static.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 535296,
  "ppid": 535292,
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "root_cargo_pid": 533330,
  "build_script_root_pid": 535282,
  "build_script_related": true,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 32

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-imultiarch",
    "aarch64-linux-gnu",
    "c-library/src/ittnotify/jitprofiling.c",
    "-quiet",
    "-dumpbase",
    "jitprofiling.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-jitprofiling.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "..."
  ],
  "src": "c-library/src/ittnotify/jitprofiling.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-jitprofiling.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 535419,
  "ppid": 535416,
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "root_cargo_pid": 533330,
  "build_script_root_pid": 535282,
  "build_script_related": true,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 33

```json
{
  "event": "archive",
  "tool": "/usr/bin/aarch64-linux-gnu-ar",
  "real_tool": "/usr/bin/aarch64-linux-gnu-ar",
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cqD",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/libittnotify.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-jitprofiling.o"
  ],
  "archive": "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/libittnotify.a",
  "objects": [
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-jitprofiling.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 535440,
  "ppid": 535282,
  "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "root_cargo_pid": 533330,
  "build_script_root_pid": 535282,
  "build_script_related": true,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T02:05:37.870580+00:00",
  "crate": "ittapi-sys",
  "version": "0.4.0",
  "architecture": "aarch64",
  "duration_seconds": 35.10006630606949,
  "trace_record_count": 30,
  "trace_owner_summary": {
    "owner_package_count": 50,
    "owner_packages": [
      {
        "crate": "windows_aarch64_gnullvm",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.52.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.6/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_gnullvm",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.52.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.6/Cargo.toml"
      },
      {
        "crate": "windows_aarch64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.52.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.6/Cargo.toml"
      },
      {
        "crate": "windows_i686_gnullvm",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnullvm@0.52.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnullvm-0.52.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnullvm-0.52.6/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_gnu",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.52.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.6/Cargo.toml"
      },
      {
        "crate": "peeking_take_while",
        "version": "0.1.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#peeking_take_while@0.1.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/peeking_take_while-0.1.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/peeking_take_while-0.1.2/Cargo.toml"
      },
      {
        "crate": "windows_i686_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.52.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.6/Cargo.toml"
      },
      {
        "crate": "windows_i686_gnu",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.52.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.6/Cargo.toml"
      },
      {
        "crate": "windows-targets",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.52.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.6/Cargo.toml"
      },
      {
        "crate": "find-msvc-tools",
        "version": "0.1.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml"
      },
      {
        "crate": "minimal-lexical",
        "version": "0.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#minimal-lexical@0.2.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/minimal-lexical-0.2.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/minimal-lexical-0.2.1/Cargo.toml"
      },
      {
        "crate": "regex-automata",
        "version": "0.4.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/Cargo.toml"
      },
      {
        "crate": "linux-raw-sys",
        "version": "0.4.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.4.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.15",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.15/Cargo.toml"
      },
      {
        "crate": "unicode-ident",
        "version": "1.0.24",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/Cargo.toml"
      },
      {
        "crate": "prettyplease",
        "version": "0.2.37",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#prettyplease@0.2.37",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prettyplease-0.2.37",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prettyplease-0.2.37/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.106",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/Cargo.toml"
      },
      {
        "crate": "regex-syntax",
        "version": "0.8.11",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.11",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/Cargo.toml"
      },
      {
        "crate": "aho-corasick",
        "version": "1.1.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4/Cargo.toml"
      },
      {
        "crate": "windows-link",
        "version": "0.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1/Cargo.toml"
      },
      {
        "crate": "windows-sys",
        "version": "0.59.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.59.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.59.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.59.0/Cargo.toml"
      },
      {
        "crate": "windows-sys",
        "version": "0.61.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.61.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2/Cargo.toml"
      },
      {
        "crate": "lazy_static",
        "version": "1.5.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.5.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0/Cargo.toml"
      },
      {
        "crate": "libloading",
        "version": "0.8.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libloading@0.8.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.8.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.8.9/Cargo.toml"
      },
      {
        "crate": "once_cell",
        "version": "1.21.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.21.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4/Cargo.toml"
      },
      {
        "crate": "rustc-hash",
        "version": "1.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustc-hash@1.1.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc-hash-1.1.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc-hash-1.1.0/Cargo.toml"
      },
      {
        "crate": "bitflags",
        "version": "2.13.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.13.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.13.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.13.0/Cargo.toml"
      },
      {
        "crate": "clang-sys",
        "version": "1.8.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#clang-sys@1.8.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clang-sys-1.8.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clang-sys-1.8.1/Cargo.toml"
      },
      {
        "crate": "bindgen",
        "version": "0.68.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bindgen@0.68.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bindgen-0.68.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bindgen-0.68.1/Cargo.toml"
      },
      {
        "crate": "lazycell",
        "version": "1.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazycell@1.3.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazycell-1.3.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazycell-1.3.0/Cargo.toml"
      },
      {
        "crate": "rustix",
        "version": "0.38.44",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@0.38.44",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.44",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.44/Cargo.toml"
      },
      {
        "crate": "either",
        "version": "1.16.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.16.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0/Cargo.toml"
      },
      {
        "crate": "cfg-if",
        "version": "1.0.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/Cargo.toml"
      },
      {
        "crate": "errno",
        "version": "0.3.14",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.14",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.14",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.14/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "2.8.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml"
      },
      {
        "crate": "quote",
        "version": "1.0.46",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/Cargo.toml"
      },
      {
        "crate": "regex",
        "version": "1.13.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.13.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0/Cargo.toml"
      },
      {
        "crate": "cexpr",
        "version": "0.6.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cexpr@0.6.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cexpr-0.6.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cexpr-0.6.0/Cargo.toml"
      },
      {
        "crate": "diff",
        "version": "0.1.13",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#diff@0.1.13",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/diff-0.1.13",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/diff-0.1.13/Cargo.toml"
      },
      {
        "crate": "home",
        "version": "0.5.12",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#home@0.5.12",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/home-0.5.12",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/home-0.5.12/Cargo.toml"
      },
      {
        "crate": "shlex",
        "version": "1.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@1.3.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0/Cargo.toml"
      },
      {
        "crate": "shlex",
        "version": "2.0.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "2.0.118",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml"
      },
      {
        "crate": "which",
        "version": "4.4.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#which@4.4.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/which-4.4.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/which-4.4.2/Cargo.toml"
      },
      {
        "crate": "glob",
        "version": "0.3.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#glob@0.3.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3/Cargo.toml"
      },
      {
        "crate": "log",
        "version": "0.4.33",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.33",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.33",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.33/Cargo.toml"
      },
      {
        "crate": "cc",
        "version": "1.2.67",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml"
      },
      {
        "crate": "nom",
        "version": "7.1.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#nom@7.1.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/nom-7.1.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/nom-7.1.3/Cargo.toml"
      },
      {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
        "manifest_path": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0/Cargo.toml"
      }
    ],
    "attributed_event_count": 16,
    "unattributed_event_count": 14,
    "owners": [
      {
        "crate": "ittapi-sys",
        "version": "0.4.0",
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
      "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "workspace_root": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.4",
          "name": "aho-corasick",
          "version": "1.1.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bindgen@0.68.1",
          "name": "bindgen",
          "version": "0.68.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bindgen-0.68.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bindgen-0.68.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.13.0",
          "name": "bitflags",
          "version": "2.13.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.13.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.13.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
          "name": "cc",
          "version": "1.2.67",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cexpr@0.6.0",
          "name": "cexpr",
          "version": "0.6.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cexpr-0.6.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cexpr-0.6.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.4",
          "name": "cfg-if",
          "version": "1.0.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#clang-sys@1.8.1",
          "name": "clang-sys",
          "version": "1.8.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clang-sys-1.8.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clang-sys-1.8.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#diff@0.1.13",
          "name": "diff",
          "version": "0.1.13",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/diff-0.1.13/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/diff-0.1.13"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.16.0",
          "name": "either",
          "version": "1.16.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.14",
          "name": "errno",
          "version": "0.3.14",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.14/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.14"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
          "name": "find-msvc-tools",
          "version": "0.1.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#glob@0.3.3",
          "name": "glob",
          "version": "0.3.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#home@0.5.12",
          "name": "home",
          "version": "0.5.12",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/home-0.5.12/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/home-0.5.12"
        },
        {
          "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
          "name": "ittapi-sys",
          "version": "0.4.0",
          "manifest_path": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.5.0",
          "name": "lazy_static",
          "version": "1.5.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazycell@1.3.0",
          "name": "lazycell",
          "version": "1.3.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazycell-1.3.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazycell-1.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
          "name": "libc",
          "version": "0.2.186",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libloading@0.8.9",
          "name": "libloading",
          "version": "0.8.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.8.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.8.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.4.15",
          "name": "linux-raw-sys",
          "version": "0.4.15",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.15/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.15"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.33",
          "name": "log",
          "version": "0.4.33",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.33/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.33"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
          "name": "memchr",
          "version": "2.8.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#minimal-lexical@0.2.1",
          "name": "minimal-lexical",
          "version": "0.2.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/minimal-lexical-0.2.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/minimal-lexical-0.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#nom@7.1.3",
          "name": "nom",
          "version": "7.1.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/nom-7.1.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/nom-7.1.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.21.4",
          "name": "once_cell",
          "version": "1.21.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#peeking_take_while@0.1.2",
          "name": "peeking_take_while",
          "version": "0.1.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/peeking_take_while-0.1.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/peeking_take_while-0.1.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#prettyplease@0.2.37",
          "name": "prettyplease",
          "version": "0.2.37",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prettyplease-0.2.37/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prettyplease-0.2.37"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
          "name": "proc-macro2",
          "version": "1.0.106",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
          "name": "quote",
          "version": "1.0.46",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.13.0",
          "name": "regex",
          "version": "1.13.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.15",
          "name": "regex-automata",
          "version": "0.4.15",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.11",
          "name": "regex-syntax",
          "version": "0.8.11",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustc-hash@1.1.0",
          "name": "rustc-hash",
          "version": "1.1.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc-hash-1.1.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc-hash-1.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@0.38.44",
          "name": "rustix",
          "version": "0.38.44",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.44/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.44"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@1.3.0",
          "name": "shlex",
          "version": "1.3.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
          "name": "shlex",
          "version": "2.0.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
          "name": "syn",
          "version": "2.0.118",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
          "name": "unicode-ident",
          "version": "1.0.24",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#which@4.4.2",
          "name": "which",
          "version": "4.4.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/which-4.4.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/which-4.4.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.1",
          "name": "windows-link",
          "version": "0.2.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.59.0",
          "name": "windows-sys",
          "version": "0.59.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.59.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.59.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.61.2",
          "name": "windows-sys",
          "version": "0.61.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.52.6",
          "name": "windows-targets",
          "version": "0.52.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.52.6",
          "name": "windows_aarch64_gnullvm",
          "version": "0.52.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.52.6",
          "name": "windows_aarch64_msvc",
          "version": "0.52.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.52.6",
          "name": "windows_i686_gnu",
          "version": "0.52.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnullvm@0.52.6",
          "name": "windows_i686_gnullvm",
          "version": "0.52.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnullvm-0.52.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnullvm-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.52.6",
          "name": "windows_i686_msvc",
          "version": "0.52.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.52.6",
          "name": "windows_x86_64_gnu",
          "version": "0.52.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.52.6",
          "name": "windows_x86_64_gnullvm",
          "version": "0.52.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
          "name": "windows_x86_64_msvc",
          "version": "0.52.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6"
        }
      ],
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 535156,
      "ppid": 535100,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ittapi-sys",
      "cargo_pkg_version": "0.4.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "event_id": "used:cc:bc9fe02df21f3b54:dc3d20b22f9d305e:31a657552161aa04",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
      "pid": 535156,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ittapi-sys",
      "cargo_pkg_version": "0.4.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "event_id": "used:cc:bc9fe02df21f3b54:fddc94802acd2bb7:31a657552161aa04",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
      "pid": 535156,
      "sha256": "f9eb66f132263251a2124a29e191966e7ba8055f629d1529645d5625bf796841",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ittapi-sys",
      "cargo_pkg_version": "0.4.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "event_id": "used:cc:bc9fe02df21f3b54:46055e5a431f99a9:31a657552161aa04",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
      "pid": 535156,
      "sha256": "8e17595a9fb41c47002abc8974f86269619bbec870550d21bd3e6601f505f063",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ittapi-sys",
      "cargo_pkg_version": "0.4.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "event_id": "used:cc:bc9fe02df21f3b54:3dcff77cb2bb205f:31a657552161aa04",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
      "pid": 535156,
      "sha256": "a48ea15d88c4623620e8c89598dd5c14b048119c024940d5455523808f0983ba",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ittapi-sys",
      "cargo_pkg_version": "0.4.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "event_id": "used:cc:bc9fe02df21f3b54:241464f73c6bfda6:31a657552161aa04",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
      "pid": 535156,
      "sha256": "c4491feae63d4722dc324571546e79c99482db08a0d6e76fb800acca485e9a94",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ittapi-sys",
      "cargo_pkg_version": "0.4.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "event_id": "used:cc:bc9fe02df21f3b54:de7f33f6a78acc8e:31a657552161aa04",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
      "pid": 535156,
      "sha256": "6dcfbe0cae6dab2cf5caf5c73e28f49315af237b002de957a58be687ab96448e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ittapi-sys",
      "cargo_pkg_version": "0.4.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "event_id": "used:cc:bc9fe02df21f3b54:5e81f3534cb5bf33:31a657552161aa04",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
      "pid": 535156,
      "sha256": "0e8c91e8502317498de977ac4fbe63e831b73f34cff11f8fe2ddafac42ea9f70",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ittapi-sys",
      "cargo_pkg_version": "0.4.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "event_id": "used:cc:bc9fe02df21f3b54:7f47abafd628d4ac:31a657552161aa04",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
      "pid": 535156,
      "sha256": "bfb00a1de9735fc70400b20a02c74907ea8edcc00dfa2a4a6afb00027658c6d4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ittapi-sys",
      "cargo_pkg_version": "0.4.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "event_id": "used:cc:bc9fe02df21f3b54:083624c412ad3e09:31a657552161aa04",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
      "pid": 535156,
      "sha256": "1e390e913e72f311b71a16e85e7be1d7349e44c86eb4706b911c279b20009c87",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ittapi-sys",
      "cargo_pkg_version": "0.4.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "event_id": "used:cc:bc9fe02df21f3b54:7b16ea71232f9d6e:31a657552161aa04",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
      "pid": 535156,
      "sha256": "b2899e985ec507a1cde58b4b2ccdd03eb8bf1259c32af93fa2e51adb7dc6beca",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
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
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "cargo_pkg_name": "ittapi-sys",
      "cargo_pkg_version": "0.4.0",
      "context_path": "/tmp/native-trace-531044-1783994705589/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-531044-1783994705589/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 535156,
      "ppid": 535100,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh",
        "/target/debug/build/ittapi-sys-153a64372a747f59",
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
          "directory": "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh",
          "kind": "object",
          "path": "/target/debug/build/ittapi-sys-153a64372a747f59/rustcgVV4Wh/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
          "kind": "object",
          "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.17973mq.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
          "kind": "object",
          "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.17973mq.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
          "kind": "object",
          "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.17973mq.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
          "kind": "object",
          "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.17973mq.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
          "kind": "object",
          "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.17973mq.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
          "kind": "object",
          "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.17973mq.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
          "kind": "object",
          "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.17973mq.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
          "kind": "object",
          "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.17973mq.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
          "kind": "object",
          "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.17973mq.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.00.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.02.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.03.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.04.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.05.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.06.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.07.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.08.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.09.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.10.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.11.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.01.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.12.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.13.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.14.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.15.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib(find_msvc_tools-60e3732174de9068.find_msvc_tools.ede48c3253d6796d-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib(find_msvc_tools-60e3732174de9068.find_msvc_tools.ede48c3253d6796d-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib(shlex-f2fa52250b1d670f.shlex.352c8e657ac65ae8-cgu.0.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-535156-1783994714120676298.map",
      "pid": 535156,
      "ppid": 535100,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-535156-1783994714120676298.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
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
      "parsed_event_count": 943,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 945,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": " ...\n17.270  collect2         538327 538325   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc49pQSP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcwrY8aa/raw-dylibs ...\n17.274  ld.lld           538328 538327   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc49pQSP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcwrY8aa/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n17.279  rust-lld         538328 538327   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc49pQSP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n17.282  rustc            538333 527474   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_protocols --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-protocols-0.31.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client\" --cfg feature=\"staging\" --cfg feature=\"unstable\" ...\n17.298  rustc            538335 527474   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_cursor --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-cursor-0.31.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=62be080b652e5042 ...\n17.304  rustc            538336 527474   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name calloop_wayland_source --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/calloop-wayland-source-0.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"log\")) -C metadata=17458c302e9afa03 ...\n17.496  rustc            538373 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-1.0.56/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n17.708  rustc            538385 532681   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde_derive --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.219/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n17.709  rustc            538389 532681   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n17.711  rustc            538390 532681   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clap_derive --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_derive-4.5.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::verbose_file_reads --warn=unused_qualifications ...\n17.712  rustc            538391 532681   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name arg_enum_proc_macro --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/arg_enum_proc_macro-0.3.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n18.360  cc               538439 538391   0 /tmp/native-trace-530685-1783994704613/shims/cc -Wl,--version-script=/target/debug/deps/rustc8wmOmz/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc8wmOmz/symbols.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.0.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.1.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.2.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.3.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.4.rcgu.o /target/debug/deps/rustc8wmOmz/rmeta.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.58q2ufzvuc8xaydmt1rvqk5d2.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-857859587c15809d.rlib /target/debug/deps/libquote-840405f79b9ea204.rlib /target/debug/deps/libproc_macro2-64766898606113cc.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- ...\n18.367  cc               538440 538439   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc8wmOmz/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc8wmOmz/symbols.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.0.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.1.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.2.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.3.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.4.rcgu.o /target/debug/deps/rustc8wmOmz/rmeta.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.58q2ufzvuc8xaydmt1rvqk5d2.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-857859587c15809d.rlib /target/debug/deps/libquote-840405f79b9ea204.rlib /target/debug/deps/libproc_macro2-64766898606113cc.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- ...\n18.373  collect2         538441 538440   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6Apxzu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc8wmOmz/raw-dylibs ...\n18.378  ld.lld           538442 538441   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6Apxzu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc8wmOmz/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.381  rust-lld         538442 538441   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6Apxzu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n18.455  runc             538461 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process2251340981 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n18.476  exe              538470 538461   0 \n18.521  etcdctl          538473 538461   0 /usr/local/bin/etcdctl endpoint health\n18.623  rustc            538495 533138   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde_derive --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.219/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n18.627  rustc            538494 533138   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n18.627  rustc            538497 533138   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clap_derive --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_derive-4.5.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::verbose_file_reads --warn=unused_qualifications ...\n18.631  cc               538498 538268   0 /tmp/native-trace-529391-1783994701958/shims/cc -Wl,--version-script=/target/debug/deps/rustcZG87GP/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcZG87GP/symbols.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.14.rcgu.o ...\n18.636  cc               538499 538498   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcZG87GP/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcZG87GP/symbols.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.14.rcgu.o ...\n18.649  rustc            538496 533138   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name arg_enum_proc_macro --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/arg_enum_proc_macro-0.3.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n18.656  collect2         538507 538499   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccx9WR7V.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcZG87GP/raw-dylibs ...\n18.661  ld.lld           538508 538507   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccx9WR7V.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcZG87GP/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.666  rust-lld         538508 538507   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccx9WR7V.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n19.048  rustc            538553 531131   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n19.241  cc               538583 538373   0 /tmp/native-trace-529392-1783994701964/shims/cc -Wl,--version-script=/target/debug/deps/rustcZYqEkq/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcZYqEkq/symbols.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.14.rcgu.o ...\n19.244  cc               538584 538583   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcZYqEkq/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcZYqEkq/symbols.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-f3801be1b6b47087.thiserror_impl.8a5b466ffeee23c3-cgu.14.rcgu.o ...\n19.248  collect2         538585 538584   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjOfd9p.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-f3801be1b6b47087.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcZYqEkq/raw-dylibs ...\n19.257  ld.lld           538586 538585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjOfd9p.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-f3801be1b6b47087.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcZYqEkq/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n19.265  rust-lld         538586 538585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjOfd9p.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-f3801be1b6b47087.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n19.273  cc               538587 538496   0 /tmp/native-trace-530944-1783994705241/shims/cc -Wl,--version-script=/target/debug/deps/rustcxTGTrN/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcxTGTrN/symbols.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.0.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.1.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.2.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.3.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.4.rcgu.o /target/debug/deps/rustcxTGTrN/rmeta.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.58q2ufzvuc8xaydmt1rvqk5d2.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-857859587c15809d.rlib /target/debug/deps/libquote-840405f79b9ea204.rlib /target/debug/deps/libproc_macro2-64766898606113cc.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- ...\n19.281  cc               538590 538587   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcxTGTrN/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcxTGTrN/symbols.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.0.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.1.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.2.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.3.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.4.rcgu.o /target/debug/deps/rustcxTGTrN/rmeta.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.58q2ufzvuc8xaydmt1rvqk5d2.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-857859587c15809d.rlib /target/debug/deps/libquote-840405f79b9ea204.rlib /target/debug/deps/libproc_macro2-64766898606113cc.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- ...\n19.282  collect2         538591 538590   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cchZzgln.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcxTGTrN/raw-dylibs ...\n19.293  ld.lld           538592 538591   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cchZzgln.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcxTGTrN/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n19.300  rust-lld         538592 538591   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cchZzgln.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n19.681  rustc            538648 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.56/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=6861f6d9a519659f ...\n19.836  cc               538664 538267   0 /tmp/native-trace-529391-1783994701958/shims/cc -Wl,--version-script=/target/debug/deps/rustcOskmb5/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcOskmb5/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n19.839  cc               538665 538664   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcOskmb5/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcOskmb5/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n19.844  collect2         538666 538665   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczyQapw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcOskmb5/raw-dylibs ...\n19.849  ld.lld           538667 538666   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczyQapw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcOskmb5/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n19.856  rust-lld         538667 538666   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczyQapw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n20.064  rustc            538697 523706   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name sctk_adwaita --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/sctk-adwaita-0.8.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"ab_glyph\" --cfg feature=\"memmap2\" --check-cfg cfg(docsrs,test) ...\n20.221  rustc            538717 531131   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clap --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.5.38/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::verbose_file_reads --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes ...\n20.442  cc               538745 538389   0 /tmp/native-trace-530685-1783994704613/shims/cc -Wl,--version-script=/target/debug/deps/rustc0RqHuC/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc0RqHuC/symbols.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.14.rcgu.o ...\n20.446  cc               538747 538745   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc0RqHuC/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc0RqHuC/symbols.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.14.rcgu.o ...\n20.461  collect2         538751 538747   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc30WuH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc0RqHuC/raw-dylibs ...\n20.466  ld.lld           538752 538751   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc30WuH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc0RqHuC/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n20.472  rust-lld         538752 538751   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc30WuH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n20.891  cc               538810 538494   0 /tmp/native-trace-530944-1783994705241/shims/cc -Wl,--version-script=/target/debug/deps/rustcCqsGXw/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcCqsGXw/symbols.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.14.rcgu.o ...\n20.894  cc               538809 538390   0 /tmp/native-trace-530685-1783994704613/shims/cc -Wl,--version-script=/target/debug/deps/rustckRDdof/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustckRDdof/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n20.900  cc               538812 538810   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcCqsGXw/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcCqsGXw/symbols.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.14.rcgu.o ...\n20.908  cc               538814 538809   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustckRDdof/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustckRDdof/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n20.914  collect2         538816 538812   0 \n20.916  ld.lld           538817 538816   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMG89yd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcCqsGXw/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n20.921  rust-lld         538817 538816   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMG89yd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n20.924  collect2         538815 538814   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnz8fQO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustckRDdof/raw-dylibs ...\n20.926  ld.lld           538818 538815   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnz8fQO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustckRDdof/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n20.928  rust-lld         538818 538815   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnz8fQO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n20.952  rustc            538821 532681   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n21.071  rustc            538867 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name polling --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/polling-3.4.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=18f523713bb5ba7f ...\n21.083  rustc            538869 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_backend --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-backend-0.3.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client_system\" --cfg feature=\"dlopen\" --check-cfg cfg(docsrs,test) ...\n21.269  16               538888 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n21.297  frpc             538888 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n21.307  rustc            538891 532681   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clap --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.5.38/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::verbose_file_reads --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes ...\n21.363  rustc            538909 533138   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n21.386  cc               538911 538497   0 /tmp/native-trace-530944-1783994705241/shims/cc -Wl,--version-script=/target/debug/deps/rustchZFaOr/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustchZFaOr/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n21.407  cc               538917 538911   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustchZFaOr/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustchZFaOr/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n21.412  collect2         538918 538917   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdaDYl3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustchZFaOr/raw-dylibs ...\n21.418  ld.lld           538919 538918   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdaDYl3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustchZFaOr/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n21.421  rust-lld         538919 538918   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdaDYl3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n21.539  rustc            538945 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name calloop --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/calloop-0.12.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"async-task\", \"block_on\", \"executor\", \"futures-io\", \"nightly_coverage\", \"nix\", \"pin-utils\", \"signals\")) -C metadata=74e7b5e683cc762c ...\n21.654  cc               538961 538262   0 /tmp/native-trace-529391-1783994701958/shims/cc -Wl,--version-script=/target/debug/deps/rustctLgo6T/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustctLgo6T/symbols.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.00.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.01.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.02.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.03.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.04.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.05.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.06.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.07.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.08.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.09.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.10.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.11.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.12.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.13.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.14.rcgu.o ...\n21.657  cc               538965 538961   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustctLgo6T/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustctLgo6T/symbols.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.00.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.01.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.02.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.03.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.04.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.05.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.06.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.07.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.08.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.09.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.10.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.11.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.12.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.13.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.14.rcgu.o ...\n21.661  collect2         538966 538965   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm6aUee.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustctLgo6T/raw-dylibs ...\n21.665  ld.lld           538967 538966   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm6aUee.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustctLgo6T/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n21.669  rust-lld         538967 538966   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm6aUee.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n21.743  rustc            538989 533138   0 \n21.854  rustc            539008 527474   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_protocols_wlr --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-protocols-wlr-0.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client\" --cfg feature=\"wayland-client\" --check-cfg cfg(docsrs,test) ...\n21.857  rustc            539007 527474   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_protocols_plasma --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-protocols-plasma-0.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client\" --cfg feature=\"wayland-client\" --check-cfg cfg(docsrs,test) ...\n21.947  rustc            539023 523706   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name winit --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"ahash\" --cfg feature=\"bytemuck\" --cfg feature=\"default\" ...\n22.026  rustc            539034 531131   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.219/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive\" --cfg feature=\"serde_derive\" ...\n"
    },
    {
      "argv": [
        "/target/debug/build/ittapi-sys-153a64372a747f59/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 535282,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/ittapi-sys-153a64372a747f59/build-script-build",
      "pid": 535282,
      "ppid": 533330,
      "root_cargo_pid": 533330,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-E",
        "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/11740837994362044329detect_compiler_family.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 535282,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 535283,
      "ppid": 535282,
      "root_cargo_pid": 533330,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-E",
        "-quiet",
        "-imultiarch",
        "aarch64-linux-gnu",
        "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/11740837994362044329detect_compiler_family.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 535282,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 535284,
      "ppid": 535283,
      "root_cargo_pid": 533330,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 535282,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 535291,
      "ppid": 535282,
      "root_cargo_pid": 533330,
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
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "c-library/src/ittnotify/",
        "-I",
        "c-library/include/",
        "-Wall",
        "-Wextra",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-ittnotify_static.o",
        "-c",
        "c-library/src/ittnotify/ittnotify_static.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 535282,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 535292,
      "ppid": 535282,
      "root_cargo_pid": 533330,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "c-library/src/ittnotify/",
        "-I",
        "c-library/include/",
        "-imultiarch",
        "aarch64-linux-gnu",
        "c-library/src/ittnotify/ittnotify_static.c",
        "-quiet",
        "-dumpbase",
        "ittnotify_static.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-ittnotify_static.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-Wall",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 535282,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 535296,
      "ppid": 535292,
      "root_cargo_pid": 533330,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-I",
        "c-library/src/ittnotify/",
        "-I",
        "c-library/include/",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-ittnotify_static.o",
        "/tmp/ccardtFs.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 535282,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 535393,
      "ppid": 535292,
      "root_cargo_pid": 533330,
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
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "c-library/src/ittnotify/",
        "-I",
        "c-library/include/",
        "-Wall",
        "-Wextra",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-jitprofiling.o",
        "-c",
        "c-library/src/ittnotify/jitprofiling.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 535282,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 535416,
      "ppid": 535282,
      "root_cargo_pid": 533330,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "c-library/src/ittnotify/",
        "-I",
        "c-library/include/",
        "-imultiarch",
        "aarch64-linux-gnu",
        "c-library/src/ittnotify/jitprofiling.c",
        "-quiet",
        "-dumpbase",
        "jitprofiling.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-jitprofiling.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-Wall",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 535282,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 535419,
      "ppid": 535416,
      "root_cargo_pid": 533330,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-I",
        "c-library/src/ittnotify/",
        "-I",
        "c-library/include/",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-jitprofiling.o",
        "/tmp/ccmxA7lO.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 535282,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 535431,
      "ppid": 535416,
      "root_cargo_pid": 533330,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "cqD",
        "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/libittnotify.a",
        "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-ittnotify_static.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/48f6f8d8d7ef524e-jitprofiling.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 535282,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 535440,
      "ppid": 535282,
      "root_cargo_pid": 533330,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "sD",
        "/target/aarch64-unknown-linux-gnu/debug/build/ittapi-sys-991e61962e29bc8b/out/libittnotify.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 535282,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 535443,
      "ppid": 535282,
      "root_cargo_pid": 533330,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "ittapi-sys",
      "cwd": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "event_id": "bsrun:e7bbd0aa31554544:cda8081d828c41f0:f2ef5110e3cd48e0",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/ittapi-sys-153a64372a747f59/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
      "out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
      "success": true,
      "target": null,
      "version": "0.4.0",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-aarch64-veh28nga/src/ittapi-sys-0.4.0",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
  "item": {
    "rank": 2212,
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "crate_id": "563273",
    "version_id": "933001",
    "downloads": 6065906,
    "cumulative_downloads": 103132552378,
    "cumulative_share_of_global": 0.38558880459189215,
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
