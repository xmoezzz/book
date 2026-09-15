# `ittapi-sys` `0.4.0`

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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI",
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
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-535954-1783994716768697683.map",
  "pid": 535954,
  "ppid": 535837,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-535954-1783994716768697683.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/libittnotify.a`

Owner: `ittapi-sys` `0.4.0`

### Source files

* `/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0/c-library/src/ittnotify/ittnotify_static.c`
* `/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0/c-library/src/ittnotify/jitprofiling.c`

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
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-Wall",
    "-Wextra",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "-c",
    "c-library/src/ittnotify/ittnotify_static.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 536092,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 536123,
  "ppid": 536092,
  "root_cargo_pid": 535231,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-Wall",
    "-Wextra",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-jitprofiling.o",
    "-c",
    "c-library/src/ittnotify/jitprofiling.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 536092,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 536414,
  "ppid": 536092,
  "root_cargo_pid": 535231,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "c-library/src/ittnotify/jitprofiling.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "jitprofiling.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-jitprofiling.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "..."
  ],
  "src": "c-library/src/ittnotify/jitprofiling.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-jitprofiling.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 536416,
  "ppid": 536414,
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "root_cargo_pid": 535231,
  "build_script_root_pid": 536092,
  "build_script_related": true,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
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
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "c-library/src/ittnotify/ittnotify_static.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "ittnotify_static.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "..."
  ],
  "src": "c-library/src/ittnotify/ittnotify_static.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-ittnotify_static.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 536136,
  "ppid": 536123,
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "root_cargo_pid": 535231,
  "build_script_root_pid": 536092,
  "build_script_related": true,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
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
    "cqD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/libittnotify.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-jitprofiling.o"
  ],
  "archive": "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/libittnotify.a",
  "objects": [
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-jitprofiling.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 536443,
  "ppid": 536092,
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "root_cargo_pid": 535231,
  "build_script_root_pid": 536092,
  "build_script_related": true,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "workspace_root": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0"
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
      "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
      "name": "ittapi-sys",
      "version": "0.4.0",
      "manifest_path": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0"
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 535954,
  "ppid": 535837,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "event_id": "used:cc:eeef2f5e857f711d:3e6432106dd7e27b:31a657552161aa04",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "path": "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
  "pid": 535954,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "event_id": "used:cc:eeef2f5e857f711d:8991dcc432338f91:31a657552161aa04",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
  "pid": 535954,
  "sha256": "5b17697e67e81a55aee615f2c9bc2ca95821db4b2201f3412981cad754d98d5c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "event_id": "used:cc:eeef2f5e857f711d:82df7378c8d769ab:31a657552161aa04",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
  "pid": 535954,
  "sha256": "d540beff0f9e9e85b57eec48b5562036ff2fa4161b7807635ed4c75994f5c588",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "event_id": "used:cc:eeef2f5e857f711d:b27a5f8267529b90:31a657552161aa04",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
  "pid": 535954,
  "sha256": "74123cdff2c53359a1c7ef9bd8b7b7fd6670841ea5e720722c164f874f060af0",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "event_id": "used:cc:eeef2f5e857f711d:6891dc617fe7bc5d:31a657552161aa04",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
  "pid": 535954,
  "sha256": "4e968ad5b1540cdc188b32184065ce7b7f26430041b4689ee5d7152399ffc84c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "event_id": "used:cc:eeef2f5e857f711d:13127c05e63d59ea:31a657552161aa04",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
  "pid": 535954,
  "sha256": "52727e3c9f9bd99485a9ac396563493f43e545e4900bf0cc5f97ca57ffffd972",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "event_id": "used:cc:eeef2f5e857f711d:de03405d94975496:31a657552161aa04",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
  "pid": 535954,
  "sha256": "ea4194aaf42015f49cd01bc2fdcd17314a352b4fc6fe0221656283a0c5fe2bcf",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "event_id": "used:cc:eeef2f5e857f711d:3eecae65b1fac064:31a657552161aa04",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
  "pid": 535954,
  "sha256": "677c9de6d85f596820a7c3eef893aebaeff6117a589cd24314a350d24f048093",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "event_id": "used:cc:eeef2f5e857f711d:7692e404b7aff8d7:31a657552161aa04",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
  "pid": 535954,
  "sha256": "4593f5ab24272c6ae9d1576c56938111e16eb5ffd2b682bbaa7a1e865eb22843",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "event_id": "used:cc:eeef2f5e857f711d:0fc290410142ad48:31a657552161aa04",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
  "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
  "pid": 535954,
  "sha256": "b2899e985ec507a1cde58b4b2ccdd03eb8bf1259c32af93fa2e51adb7dc6beca",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "cargo_pkg_name": "ittapi-sys",
  "cargo_pkg_version": "0.4.0",
  "context_path": "/tmp/native-trace-532725-1783994709756/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-532725-1783994709756/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 535954,
  "ppid": 535837,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
    "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI",
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
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
      "kind": "object",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-535954-1783994716768697683.map",
  "pid": 535954,
  "ppid": 535837,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-535954-1783994716768697683.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
  "parsed_event_count": 664,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 666,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.3.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.4.rcgu.o /target/debug/deps/rustcxTGTrN/rmeta.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.58q2ufzvuc8xaydmt1rvqk5d2.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-857859587c15809d.rlib /target/debug/deps/libquote-840405f79b9ea204.rlib /target/debug/deps/libproc_macro2-64766898606113cc.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- ...\n15.511  collect2         538591 538590   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cchZzgln.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcxTGTrN/raw-dylibs ...\n15.520  ld.lld           538592 538591   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cchZzgln.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcxTGTrN/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n15.527  rust-lld         538592 538591   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cchZzgln.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n15.909  rustc            538648 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.56/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=6861f6d9a519659f ...\n16.063  cc               538664 538267   0 /tmp/native-trace-529391-1783994701958/shims/cc -Wl,--version-script=/target/debug/deps/rustcOskmb5/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcOskmb5/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n16.066  cc               538665 538664   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcOskmb5/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcOskmb5/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n16.072  collect2         538666 538665   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczyQapw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcOskmb5/raw-dylibs ...\n16.076  ld.lld           538667 538666   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczyQapw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcOskmb5/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n16.083  rust-lld         538667 538666   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczyQapw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n16.296  rustc            538697 523706   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name sctk_adwaita --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/sctk-adwaita-0.8.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"ab_glyph\" --cfg feature=\"memmap2\" --check-cfg cfg(docsrs,test) ...\n16.447  rustc            538717 531131   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clap --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.5.38/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::verbose_file_reads --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes ...\n16.670  cc               538745 538389   0 /tmp/native-trace-530685-1783994704613/shims/cc -Wl,--version-script=/target/debug/deps/rustc0RqHuC/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc0RqHuC/symbols.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.14.rcgu.o ...\n16.672  cc               538747 538745   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc0RqHuC/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc0RqHuC/symbols.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.14.rcgu.o ...\n16.689  collect2         538751 538747   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc30WuH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc0RqHuC/raw-dylibs ...\n16.693  ld.lld           538752 538751   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc30WuH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc0RqHuC/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n16.700  rust-lld         538752 538751   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc30WuH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n17.119  cc               538810 538494   0 /tmp/native-trace-530944-1783994705241/shims/cc -Wl,--version-script=/target/debug/deps/rustcCqsGXw/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcCqsGXw/symbols.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.14.rcgu.o ...\n17.122  cc               538809 538390   0 /tmp/native-trace-530685-1783994704613/shims/cc -Wl,--version-script=/target/debug/deps/rustckRDdof/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustckRDdof/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n17.128  cc               538812 538810   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcCqsGXw/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcCqsGXw/symbols.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.14.rcgu.o ...\n17.136  cc               538814 538809   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustckRDdof/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustckRDdof/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n17.146  collect2         538816 538812   0 \n17.146  ld.lld           538817 538816   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMG89yd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcCqsGXw/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n17.151  rust-lld         538817 538816   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMG89yd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n17.151  collect2         538815 538814   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnz8fQO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustckRDdof/raw-dylibs ...\n17.154  ld.lld           538818 538815   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnz8fQO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustckRDdof/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n17.157  rust-lld         538818 538815   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnz8fQO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n17.179  rustc            538821 532681   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n17.299  rustc            538867 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name polling --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/polling-3.4.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=18f523713bb5ba7f ...\n17.310  rustc            538869 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_backend --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-backend-0.3.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client_system\" --cfg feature=\"dlopen\" --check-cfg cfg(docsrs,test) ...\n17.496  16               538888 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n17.524  frpc             538888 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n17.534  rustc            538891 532681   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clap --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.5.38/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::verbose_file_reads --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes ...\n17.591  rustc            538909 533138   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n17.614  cc               538911 538497   0 /tmp/native-trace-530944-1783994705241/shims/cc -Wl,--version-script=/target/debug/deps/rustchZFaOr/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustchZFaOr/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n17.635  cc               538917 538911   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustchZFaOr/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustchZFaOr/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n17.640  collect2         538918 538917   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdaDYl3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustchZFaOr/raw-dylibs ...\n17.645  ld.lld           538919 538918   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdaDYl3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustchZFaOr/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n17.649  rust-lld         538919 538918   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdaDYl3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n17.766  rustc            538945 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name calloop --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/calloop-0.12.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"async-task\", \"block_on\", \"executor\", \"futures-io\", \"nightly_coverage\", \"nix\", \"pin-utils\", \"signals\")) -C metadata=74e7b5e683cc762c ...\n17.881  cc               538961 538262   0 /tmp/native-trace-529391-1783994701958/shims/cc -Wl,--version-script=/target/debug/deps/rustctLgo6T/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustctLgo6T/symbols.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.00.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.01.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.02.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.03.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.04.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.05.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.06.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.07.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.08.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.09.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.10.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.11.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.12.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.13.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.14.rcgu.o ...\n17.884  cc               538965 538961   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustctLgo6T/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustctLgo6T/symbols.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.00.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.01.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.02.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.03.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.04.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.05.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.06.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.07.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.08.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.09.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.10.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.11.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.12.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.13.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.14.rcgu.o ...\n17.889  collect2         538966 538965   0 \n17.892  ld.lld           538967 538966   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm6aUee.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustctLgo6T/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n17.896  rust-lld         538967 538966   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm6aUee.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n17.968  rustc            538989 533138   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clap --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.5.38/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::verbose_file_reads --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes ...\n18.081  rustc            539008 527474   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_protocols_wlr --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-protocols-wlr-0.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client\" --cfg feature=\"wayland-client\" --check-cfg cfg(docsrs,test) ...\n18.085  rustc            539007 527474   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_protocols_plasma --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-protocols-plasma-0.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client\" --cfg feature=\"wayland-client\" --check-cfg cfg(docsrs,test) ...\n18.174  rustc            539023 523706   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name winit --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"ahash\" --cfg feature=\"bytemuck\" --cfg feature=\"default\" ...\n18.258  rustc            539034 531131   0 \n18.323  runc             539041 530954   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aafefb44939d6dbe4936f6fb1cfd21d4fddf1e9d5d85cf1742a04f2fd38 --log-format json --systemd-cgroup kill --all aafefb44939d6dbe4936f6fb1cfd21d4fddf1e9d5d85cf1742a04f2fd3872d69 9\n18.361  runc             539050 530954   0 \n18.562  containerd-shim  539072 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id aafefb44939d6dbe4936f6fb1cfd21d4fddf1e9d5d85cf1742a04f2fd3872d69 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aafefb44939d6dbe4936f6fb1cfd21d4fddf1e9d5d85cf1742a04f2fd38 delete\n18.566  runc             539080 539072   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aafefb44939d6dbe4936f6fb1cfd21d4fddf1e9d5d85cf1742a04f2fd3872d6 --log-format json delete --force aafefb44939d6dbe4936f6fb1cfd21d4fddf1e9d5d85cf1742a04f2fd3872d69\n18.631  sh               539093 539089   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth926b649\n18.635  ethtool          539094 539093   0 /usr/sbin/ethtool -i veth926b649\n18.635  sed              539095 539093   0 /usr/bin/sed -n s/^driver: //p\n18.648  systemd-sysctl   539098 539089   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth926b649 --prefix=/net/ipv4/neigh/veth926b649 --prefix=/net/ipv6/conf/veth926b649 --prefix=/net/ipv6/neigh/veth926b649\n18.918  cc               539122 538385   0 /tmp/native-trace-530685-1783994704613/shims/cc -Wl,--version-script=/target/debug/deps/rustc4dr5JQ/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc4dr5JQ/symbols.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.00.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.01.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.02.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.03.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.04.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.05.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.06.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.07.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.08.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.09.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.10.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.11.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.12.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.13.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.14.rcgu.o ...\n18.920  cc               539124 539122   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc4dr5JQ/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc4dr5JQ/symbols.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.00.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.01.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.02.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.03.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.04.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.05.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.06.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.07.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.08.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.09.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.10.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.11.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.12.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.13.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.14.rcgu.o ...\n18.925  collect2         539125 539124   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccQ3iIId.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc4dr5JQ/raw-dylibs ...\n18.928  ld.lld           539126 539125   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccQ3iIId.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc4dr5JQ/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.931  rust-lld         539126 539125   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccQ3iIId.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n18.976  cc               539142 538495   0 /tmp/native-trace-530944-1783994705241/shims/cc -Wl,--version-script=/target/debug/deps/rustc6OE2fP/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc6OE2fP/symbols.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.00.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.01.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.02.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.03.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.04.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.05.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.06.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.07.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.08.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.09.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.10.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.11.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.12.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.13.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.14.rcgu.o ...\n18.976  cc               539146 539142   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc6OE2fP/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc6OE2fP/symbols.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.00.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.01.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.02.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.03.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.04.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.05.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.06.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.07.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.08.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.09.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.10.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.11.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.12.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.13.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.14.rcgu.o ...\n18.982  collect2         539147 539146   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccyETRQV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc6OE2fP/raw-dylibs ...\n18.984  ld.lld           539148 539147   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccyETRQV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc6OE2fP/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.988  rust-lld         539148 539147   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccyETRQV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n19.005  rustc            539154 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_csd_frame --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-csd-frame-0.3.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=8e84865feddce59c ...\n19.007  rustc            539153 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_client --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-client-0.31.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"log\")) -C metadata=59b84131929389da ...\n19.262  rustc            539191 532681   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.219/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive\" --cfg feature=\"serde_derive\" ...\n19.299  rustc            539196 533138   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.219/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive\" --cfg feature=\"serde_derive\" ...\n19.609  rustc            539203 527474   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name smithay_client_toolkit --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/smithay-client-toolkit-0.18.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"calloop\" --cfg feature=\"calloop-wayland-source\" --check-cfg cfg(docsrs,test) ...\n19.860  rustc            539218 527474   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name x11rb --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/x11rb-0.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"allow-unsafe-code\" --cfg feature=\"as-raw-xcb-connection\" --cfg feature=\"dl-libxcb\" ...\n19.978  rustc            539229 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name calloop_wayland_source --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/calloop-wayland-source-0.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"log\")) -C metadata=974aaa993087e5d0 ...\n19.978  rustc            539227 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_cursor --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-cursor-0.31.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=bf5a79308c3aaa46 ...\n19.979  rustc            539228 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_protocols --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-protocols-0.31.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client\" --cfg feature=\"staging\" --cfg feature=\"unstable\" ...\n20.129  runc             539251 523244   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f82cb79421275c0a2277f2bea92e76ce3b69ae69348bbff53d6f7fb9332 --log-format json --systemd-cgroup kill --all f82cb79421275c0a2277f2bea92e76ce3b69ae69348bbff53d6f7fb93321cfa7 9\n20.147  runc             539258 523244   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f82cb79421275c0a2277f2bea92e76ce3b69ae69348bbff53d6f7fb9332 --log-format json --systemd-cgroup delete f82cb79421275c0a2277f2bea92e76ce3b69ae69348bbff53d6f7fb93321cfa7\n20.157  cross            539264 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n20.163  rustc            539265 539264   0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.168  cross            539276 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.169  rustc            539277 539276   0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.180  rustc            539265 539264   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.181  rustc            539277 539276   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.190  rustc            539292 539264   0 /home/xmoe/.cargo/bin/rustc -vV\n20.205  rustc            539304 539276   0 /home/xmoe/.cargo/bin/rustc -vV\n20.213  rustc            539304 539276   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.226  cross            539315 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n20.227  rustc            539318 539315   0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.228  cargo            539319 539276   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.239  rustc            539318 539315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.242  cargo            539319 539276   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.257  rustc            539339 539315   0 /home/xmoe/.cargo/bin/rustc -vV\n20.261  rustc            539340 539319   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.269  rustc            539292 539264   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.275  rustc            539339 539315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.282  rustc            539350 539319   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.289  cargo            539352 539264   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.293  cargo            539354 539315   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n20.299  cargo            539352 539264   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.303  rustc            539368 539319   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.319  rustc            539378 539352   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.319  cargo            539354 539315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n20.331  rustc            539381 539354   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.332  rustc            539382 539352   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.343  rustc            539384 539354   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.354  rustc            539388 539352   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.365  rustc            539395 539354   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.390  rustc            539402 539276   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n20.397  rustc            539402 539276   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n20.412  containerd-shim  539416 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f82cb79421275c0a2277f2bea92e76ce3b69ae69348bbff53d6f7fb93321cfa7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f82cb79421275c0a2277f2bea92e76ce3b69ae69348bbff53d6f7fb9332 delete\n20.420  runc             539424 539416   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f82cb79421275c0a2277f2bea92e76ce3b69ae69348bbff53d6f7fb93321cfa --log-format json delete --force f82cb79421275c0a2277f2bea92e76ce3b69ae69348bbff53d6f7fb93321cfa7\n20.426  rustc            539429 539264   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n20.437  rustc            539429 539264   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n20.456  docker           539444 539264   0 /usr/bin/docker --help\n20.483  docker           539453 539264   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n20.487  systemd-sysctl   539459 539089   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2e612e7 --prefix=/net/ipv4/neigh/veth2e612e7 --prefix=/net/ipv6/conf/veth2e612e7 --prefix=/net/ipv6/neigh/veth2e612e7\n20.529  docker           539467 539276   0 /usr/bin/docker --help\n20.540  runc             539474 1599     0 /usr/bin/runc --version\n20.546  docker-init      539485 1599     0 /usr/bin/docker-init --version\n20.549  docker           539486 539264   0 /usr/bin/docker info -f {{.SecurityOptions}}\n20.579  runc             539495 1599     0 /usr/bin/runc --version\n20.584  rustup           539501 522103   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n20.586  docker-init      539502 1599     0 /usr/bin/docker-init --version\n20.628  rustup           539515 539264   0 /home/xmoe/.cargo/bin/rustup toolchain list\n20.641  rustup           539524 539264   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n20.655  docker           539534 539276   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n20.675  runc             539543 1599     0 /usr/bin/runc --version\n20.681  docker-init      539549 1599     0 /usr/bin/docker-init --version\n20.685  docker           539551 539276   0 /usr/bin/docker info -f {{.SecurityOptions}}\n20.687  rustup           539552 539264   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n20.696  rustc            539566 539354   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.717  runc             539572 1599     0 /usr/bin/runc --version\n20.722  docker-init      539578 1599     0 /usr/bin/docker-init --version\n20.744  uname            539581 539264   0 /usr/bin/uname -r\n20.769  rustup           539586 539276   0 /home/xmoe/.cargo/bin/rustup toolchain list\n20.779  rustup           539596 539276   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n20.783  docker           539597 539264   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n20.789  rustc            539584 527474   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name sctk_adwaita --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/sctk-adwaita-0.8.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"ab_glyph\" --cfg feature=\"memmap2\" --check-cfg cfg(docsrs,test) ...\n20.839  rustup           539623 539276   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n20.882  uname            539634 539276   0 /usr/bin/uname -r\n20.897  rustc            539635 539315   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n"
}
```

#### Record 18

```json
{
  "argv": [
    "/target/debug/build/ittapi-sys-153a64372a747f59/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 536092,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/ittapi-sys-153a64372a747f59/build-script-build",
  "pid": 536092,
  "ppid": 535231,
  "root_cargo_pid": 535231,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out"
}
```

#### Record 19

```json
{
  "argv": [],
  "build_script_related": true,
  "build_script_root_pid": 536092,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "powerpc64le-lin",
  "pid": 536099,
  "ppid": 536092,
  "root_cargo_pid": 535231,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 20

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-E",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/8161832041459257609detect_compiler_family.c",
    "-msecure-plt",
    "-mcpu=power8",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 536092,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 536100,
  "ppid": 536099,
  "root_cargo_pid": 535231,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 21

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 536092,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 536114,
  "ppid": 536092,
  "root_cargo_pid": 535231,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_cwd_recovered_from_build_script_run": true
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
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-Wall",
    "-Wextra",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "-c",
    "c-library/src/ittnotify/ittnotify_static.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 536092,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 536123,
  "ppid": 536092,
  "root_cargo_pid": 535231,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "c-library/src/ittnotify/ittnotify_static.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "ittnotify_static.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 536092,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 536136,
  "ppid": 536123,
  "root_cargo_pid": 535231,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 24

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "/tmp/cc1VdPKi.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 536092,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 536400,
  "ppid": 536123,
  "root_cargo_pid": 535231,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 25

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-Wall",
    "-Wextra",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-jitprofiling.o",
    "-c",
    "c-library/src/ittnotify/jitprofiling.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 536092,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 536414,
  "ppid": 536092,
  "root_cargo_pid": 535231,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 26

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "c-library/src/ittnotify/jitprofiling.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "jitprofiling.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-jitprofiling.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 536092,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 536416,
  "ppid": 536414,
  "root_cargo_pid": 535231,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 27

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-jitprofiling.o",
    "/tmp/ccDXE7wk.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 536092,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 536431,
  "ppid": 536414,
  "root_cargo_pid": 535231,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 28

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cqD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/libittnotify.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-jitprofiling.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 536092,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 536443,
  "ppid": 536092,
  "root_cargo_pid": 535231,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 29

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "sD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/libittnotify.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 536092,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 536450,
  "ppid": 536092,
  "root_cargo_pid": 535231,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 30

```json
{
  "crate": "ittapi-sys",
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "event_id": "bsrun:96e9f481375da5c2:cda8081d828c41f0:f2ef5110e3cd48e0",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/ittapi-sys-153a64372a747f59/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
  "success": true,
  "target": null,
  "version": "0.4.0",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  }
}
```

#### Record 31

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "c-library/src/ittnotify/ittnotify_static.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "ittnotify_static.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "..."
  ],
  "src": "c-library/src/ittnotify/ittnotify_static.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-ittnotify_static.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 536136,
  "ppid": 536123,
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "root_cargo_pid": 535231,
  "build_script_root_pid": 536092,
  "build_script_related": true,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 32

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "c-library/src/ittnotify/",
    "-I",
    "c-library/include/",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "c-library/src/ittnotify/jitprofiling.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "jitprofiling.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-jitprofiling.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "..."
  ],
  "src": "c-library/src/ittnotify/jitprofiling.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-jitprofiling.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 536416,
  "ppid": 536414,
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "root_cargo_pid": 535231,
  "build_script_root_pid": 536092,
  "build_script_related": true,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 33

```json
{
  "event": "archive",
  "tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "real_tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cqD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/libittnotify.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-jitprofiling.o"
  ],
  "archive": "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/libittnotify.a",
  "objects": [
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-ittnotify_static.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-jitprofiling.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 536443,
  "ppid": 536092,
  "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "root_cargo_pid": 535231,
  "build_script_root_pid": 536092,
  "build_script_related": true,
  "build_script_target_dir": "ittapi-sys-153a64372a747f59",
  "_owner": {
    "crate": "ittapi-sys",
    "version": "0.4.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
  "_build_script_out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T02:05:40.520153+00:00",
  "crate": "ittapi-sys",
  "version": "0.4.0",
  "architecture": "ppc64le",
  "duration_seconds": 36.68545818096027,
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
        "manifest_path": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0/Cargo.toml"
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
      "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "workspace_root": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0"
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
          "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
          "name": "ittapi-sys",
          "version": "0.4.0",
          "manifest_path": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0"
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 535954,
      "ppid": 535837,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "event_id": "used:cc:eeef2f5e857f711d:3e6432106dd7e27b:31a657552161aa04",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
      "pid": 535954,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "event_id": "used:cc:eeef2f5e857f711d:8991dcc432338f91:31a657552161aa04",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
      "pid": 535954,
      "sha256": "5b17697e67e81a55aee615f2c9bc2ca95821db4b2201f3412981cad754d98d5c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "event_id": "used:cc:eeef2f5e857f711d:82df7378c8d769ab:31a657552161aa04",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
      "pid": 535954,
      "sha256": "d540beff0f9e9e85b57eec48b5562036ff2fa4161b7807635ed4c75994f5c588",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "event_id": "used:cc:eeef2f5e857f711d:b27a5f8267529b90:31a657552161aa04",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
      "pid": 535954,
      "sha256": "74123cdff2c53359a1c7ef9bd8b7b7fd6670841ea5e720722c164f874f060af0",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "event_id": "used:cc:eeef2f5e857f711d:6891dc617fe7bc5d:31a657552161aa04",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
      "pid": 535954,
      "sha256": "4e968ad5b1540cdc188b32184065ce7b7f26430041b4689ee5d7152399ffc84c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "event_id": "used:cc:eeef2f5e857f711d:13127c05e63d59ea:31a657552161aa04",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
      "pid": 535954,
      "sha256": "52727e3c9f9bd99485a9ac396563493f43e545e4900bf0cc5f97ca57ffffd972",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "event_id": "used:cc:eeef2f5e857f711d:de03405d94975496:31a657552161aa04",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
      "pid": 535954,
      "sha256": "ea4194aaf42015f49cd01bc2fdcd17314a352b4fc6fe0221656283a0c5fe2bcf",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "event_id": "used:cc:eeef2f5e857f711d:3eecae65b1fac064:31a657552161aa04",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
      "pid": 535954,
      "sha256": "677c9de6d85f596820a7c3eef893aebaeff6117a589cd24314a350d24f048093",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "event_id": "used:cc:eeef2f5e857f711d:7692e404b7aff8d7:31a657552161aa04",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
      "pid": 535954,
      "sha256": "4593f5ab24272c6ae9d1576c56938111e16eb5ffd2b682bbaa7a1e865eb22843",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "event_id": "used:cc:eeef2f5e857f711d:0fc290410142ad48:31a657552161aa04",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59",
      "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
      "pid": 535954,
      "sha256": "b2899e985ec507a1cde58b4b2ccdd03eb8bf1259c32af93fa2e51adb7dc6beca",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "cargo_pkg_name": "ittapi-sys",
      "cargo_pkg_version": "0.4.0",
      "context_path": "/tmp/native-trace-532725-1783994709756/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-532725-1783994709756/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 535954,
      "ppid": 535837,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
        "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI",
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
          "directory": "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI",
          "kind": "object",
          "path": "/target/debug/build/ittapi-sys-153a64372a747f59/rustcol7JPI/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
          "kind": "object",
          "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.10dte9zlvu4y6gh2znsfdjuq9.0mc6at8.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
          "kind": "object",
          "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.11xwrg80utv4inyz94yoqz8z0.0mc6at8.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
          "kind": "object",
          "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.29fuq1wf66iopp2y5ehluzjpp.0mc6at8.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
          "kind": "object",
          "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.2s3dd21qb737x782hpfqmhylu.0mc6at8.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
          "kind": "object",
          "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.b3stdxfthvfp258q9ggt95xbd.0mc6at8.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
          "kind": "object",
          "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dpi9ontyxjp7rvwmyqoleo51e.0mc6at8.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
          "kind": "object",
          "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.dxcoj4rze3jpl9jger72vku6t.0mc6at8.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
          "kind": "object",
          "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.ebepygeiocgo8akyn0xfsieia.0mc6at8.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ittapi-sys-153a64372a747f59",
          "kind": "object",
          "path": "/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59.5w1gxwwgxn5wf1ql7latescw7.0mc6at8.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-535954-1783994716768697683.map",
      "pid": 535954,
      "ppid": 535837,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-535954-1783994716768697683.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
      "parsed_event_count": 664,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 666,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.3.rcgu.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.arg_enum_proc_macro.3abc8ce77d88a0a7-cgu.4.rcgu.o /target/debug/deps/rustcxTGTrN/rmeta.o /target/debug/deps/arg_enum_proc_macro-60953c67e6655d17.58q2ufzvuc8xaydmt1rvqk5d2.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-857859587c15809d.rlib /target/debug/deps/libquote-840405f79b9ea204.rlib /target/debug/deps/libproc_macro2-64766898606113cc.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- ...\n15.511  collect2         538591 538590   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cchZzgln.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcxTGTrN/raw-dylibs ...\n15.520  ld.lld           538592 538591   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cchZzgln.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcxTGTrN/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n15.527  rust-lld         538592 538591   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cchZzgln.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libarg_enum_proc_macro-60953c67e6655d17.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n15.909  rustc            538648 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.56/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=6861f6d9a519659f ...\n16.063  cc               538664 538267   0 /tmp/native-trace-529391-1783994701958/shims/cc -Wl,--version-script=/target/debug/deps/rustcOskmb5/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcOskmb5/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n16.066  cc               538665 538664   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcOskmb5/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcOskmb5/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n16.072  collect2         538666 538665   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczyQapw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcOskmb5/raw-dylibs ...\n16.076  ld.lld           538667 538666   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczyQapw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcOskmb5/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n16.083  rust-lld         538667 538666   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczyQapw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n16.296  rustc            538697 523706   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name sctk_adwaita --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/sctk-adwaita-0.8.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"ab_glyph\" --cfg feature=\"memmap2\" --check-cfg cfg(docsrs,test) ...\n16.447  rustc            538717 531131   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clap --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.5.38/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::verbose_file_reads --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes ...\n16.670  cc               538745 538389   0 /tmp/native-trace-530685-1783994704613/shims/cc -Wl,--version-script=/target/debug/deps/rustc0RqHuC/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc0RqHuC/symbols.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.14.rcgu.o ...\n16.672  cc               538747 538745   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc0RqHuC/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc0RqHuC/symbols.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.14.rcgu.o ...\n16.689  collect2         538751 538747   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc30WuH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc0RqHuC/raw-dylibs ...\n16.693  ld.lld           538752 538751   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc30WuH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc0RqHuC/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n16.700  rust-lld         538752 538751   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc30WuH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n17.119  cc               538810 538494   0 /tmp/native-trace-530944-1783994705241/shims/cc -Wl,--version-script=/target/debug/deps/rustcCqsGXw/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcCqsGXw/symbols.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.14.rcgu.o ...\n17.122  cc               538809 538390   0 /tmp/native-trace-530685-1783994704613/shims/cc -Wl,--version-script=/target/debug/deps/rustckRDdof/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustckRDdof/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n17.128  cc               538812 538810   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcCqsGXw/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcCqsGXw/symbols.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-56caefa0cb1d6d43.thiserror_impl.6b33f44a132179f3-cgu.14.rcgu.o ...\n17.136  cc               538814 538809   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustckRDdof/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustckRDdof/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n17.146  collect2         538816 538812   0 \n17.146  ld.lld           538817 538816   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMG89yd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcCqsGXw/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n17.151  rust-lld         538817 538816   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMG89yd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-56caefa0cb1d6d43.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n17.151  collect2         538815 538814   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnz8fQO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustckRDdof/raw-dylibs ...\n17.154  ld.lld           538818 538815   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnz8fQO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustckRDdof/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n17.157  rust-lld         538818 538815   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnz8fQO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n17.179  rustc            538821 532681   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n17.299  rustc            538867 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name polling --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/polling-3.4.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=18f523713bb5ba7f ...\n17.310  rustc            538869 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_backend --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-backend-0.3.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client_system\" --cfg feature=\"dlopen\" --check-cfg cfg(docsrs,test) ...\n17.496  16               538888 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n17.524  frpc             538888 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n17.534  rustc            538891 532681   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clap --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.5.38/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::verbose_file_reads --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes ...\n17.591  rustc            538909 533138   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n17.614  cc               538911 538497   0 /tmp/native-trace-530944-1783994705241/shims/cc -Wl,--version-script=/target/debug/deps/rustchZFaOr/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustchZFaOr/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n17.635  cc               538917 538911   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustchZFaOr/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustchZFaOr/symbols.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.00.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.01.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.02.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.03.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.04.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.05.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.06.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.07.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.08.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.09.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.10.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.11.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.12.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.13.rcgu.o /target/debug/deps/clap_derive-a166043b61f8c336.clap_derive.20458de4b1143d19-cgu.14.rcgu.o ...\n17.640  collect2         538918 538917   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdaDYl3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustchZFaOr/raw-dylibs ...\n17.645  ld.lld           538919 538918   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdaDYl3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustchZFaOr/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n17.649  rust-lld         538919 538918   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdaDYl3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libclap_derive-a166043b61f8c336.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n17.766  rustc            538945 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name calloop --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/calloop-0.12.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"async-task\", \"block_on\", \"executor\", \"futures-io\", \"nightly_coverage\", \"nix\", \"pin-utils\", \"signals\")) -C metadata=74e7b5e683cc762c ...\n17.881  cc               538961 538262   0 /tmp/native-trace-529391-1783994701958/shims/cc -Wl,--version-script=/target/debug/deps/rustctLgo6T/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustctLgo6T/symbols.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.00.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.01.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.02.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.03.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.04.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.05.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.06.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.07.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.08.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.09.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.10.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.11.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.12.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.13.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.14.rcgu.o ...\n17.884  cc               538965 538961   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustctLgo6T/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustctLgo6T/symbols.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.00.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.01.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.02.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.03.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.04.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.05.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.06.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.07.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.08.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.09.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.10.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.11.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.12.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.13.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.14.rcgu.o ...\n17.889  collect2         538966 538965   0 \n17.892  ld.lld           538967 538966   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm6aUee.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustctLgo6T/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n17.896  rust-lld         538967 538966   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm6aUee.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n17.968  rustc            538989 533138   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clap --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.5.38/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::verbose_file_reads --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes ...\n18.081  rustc            539008 527474   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_protocols_wlr --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-protocols-wlr-0.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client\" --cfg feature=\"wayland-client\" --check-cfg cfg(docsrs,test) ...\n18.085  rustc            539007 527474   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_protocols_plasma --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-protocols-plasma-0.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client\" --cfg feature=\"wayland-client\" --check-cfg cfg(docsrs,test) ...\n18.174  rustc            539023 523706   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name winit --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"ahash\" --cfg feature=\"bytemuck\" --cfg feature=\"default\" ...\n18.258  rustc            539034 531131   0 \n18.323  runc             539041 530954   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aafefb44939d6dbe4936f6fb1cfd21d4fddf1e9d5d85cf1742a04f2fd38 --log-format json --systemd-cgroup kill --all aafefb44939d6dbe4936f6fb1cfd21d4fddf1e9d5d85cf1742a04f2fd3872d69 9\n18.361  runc             539050 530954   0 \n18.562  containerd-shim  539072 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id aafefb44939d6dbe4936f6fb1cfd21d4fddf1e9d5d85cf1742a04f2fd3872d69 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aafefb44939d6dbe4936f6fb1cfd21d4fddf1e9d5d85cf1742a04f2fd38 delete\n18.566  runc             539080 539072   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aafefb44939d6dbe4936f6fb1cfd21d4fddf1e9d5d85cf1742a04f2fd3872d6 --log-format json delete --force aafefb44939d6dbe4936f6fb1cfd21d4fddf1e9d5d85cf1742a04f2fd3872d69\n18.631  sh               539093 539089   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth926b649\n18.635  ethtool          539094 539093   0 /usr/sbin/ethtool -i veth926b649\n18.635  sed              539095 539093   0 /usr/bin/sed -n s/^driver: //p\n18.648  systemd-sysctl   539098 539089   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth926b649 --prefix=/net/ipv4/neigh/veth926b649 --prefix=/net/ipv6/conf/veth926b649 --prefix=/net/ipv6/neigh/veth926b649\n18.918  cc               539122 538385   0 /tmp/native-trace-530685-1783994704613/shims/cc -Wl,--version-script=/target/debug/deps/rustc4dr5JQ/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc4dr5JQ/symbols.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.00.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.01.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.02.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.03.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.04.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.05.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.06.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.07.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.08.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.09.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.10.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.11.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.12.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.13.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.14.rcgu.o ...\n18.920  cc               539124 539122   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc4dr5JQ/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc4dr5JQ/symbols.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.00.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.01.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.02.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.03.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.04.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.05.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.06.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.07.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.08.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.09.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.10.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.11.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.12.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.13.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.14.rcgu.o ...\n18.925  collect2         539125 539124   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccQ3iIId.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc4dr5JQ/raw-dylibs ...\n18.928  ld.lld           539126 539125   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccQ3iIId.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc4dr5JQ/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.931  rust-lld         539126 539125   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccQ3iIId.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n18.976  cc               539142 538495   0 /tmp/native-trace-530944-1783994705241/shims/cc -Wl,--version-script=/target/debug/deps/rustc6OE2fP/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc6OE2fP/symbols.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.00.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.01.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.02.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.03.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.04.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.05.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.06.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.07.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.08.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.09.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.10.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.11.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.12.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.13.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.14.rcgu.o ...\n18.976  cc               539146 539142   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc6OE2fP/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc6OE2fP/symbols.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.00.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.01.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.02.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.03.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.04.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.05.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.06.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.07.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.08.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.09.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.10.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.11.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.12.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.13.rcgu.o /target/debug/deps/serde_derive-6c831667e0cfbc3b.serde_derive.cd27af480bef6701-cgu.14.rcgu.o ...\n18.982  collect2         539147 539146   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccyETRQV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc6OE2fP/raw-dylibs ...\n18.984  ld.lld           539148 539147   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccyETRQV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc6OE2fP/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.988  rust-lld         539148 539147   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccyETRQV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-6c831667e0cfbc3b.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n19.005  rustc            539154 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_csd_frame --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-csd-frame-0.3.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=8e84865feddce59c ...\n19.007  rustc            539153 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_client --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-client-0.31.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"log\")) -C metadata=59b84131929389da ...\n19.262  rustc            539191 532681   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.219/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive\" --cfg feature=\"serde_derive\" ...\n19.299  rustc            539196 533138   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.219/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive\" --cfg feature=\"serde_derive\" ...\n19.609  rustc            539203 527474   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name smithay_client_toolkit --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/smithay-client-toolkit-0.18.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"calloop\" --cfg feature=\"calloop-wayland-source\" --check-cfg cfg(docsrs,test) ...\n19.860  rustc            539218 527474   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name x11rb --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/x11rb-0.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"allow-unsafe-code\" --cfg feature=\"as-raw-xcb-connection\" --cfg feature=\"dl-libxcb\" ...\n19.978  rustc            539229 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name calloop_wayland_source --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/calloop-wayland-source-0.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"log\")) -C metadata=974aaa993087e5d0 ...\n19.978  rustc            539227 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_cursor --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-cursor-0.31.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=bf5a79308c3aaa46 ...\n19.979  rustc            539228 531130   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wayland_protocols --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-protocols-0.31.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"client\" --cfg feature=\"staging\" --cfg feature=\"unstable\" ...\n20.129  runc             539251 523244   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f82cb79421275c0a2277f2bea92e76ce3b69ae69348bbff53d6f7fb9332 --log-format json --systemd-cgroup kill --all f82cb79421275c0a2277f2bea92e76ce3b69ae69348bbff53d6f7fb93321cfa7 9\n20.147  runc             539258 523244   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f82cb79421275c0a2277f2bea92e76ce3b69ae69348bbff53d6f7fb9332 --log-format json --systemd-cgroup delete f82cb79421275c0a2277f2bea92e76ce3b69ae69348bbff53d6f7fb93321cfa7\n20.157  cross            539264 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n20.163  rustc            539265 539264   0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.168  cross            539276 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.169  rustc            539277 539276   0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.180  rustc            539265 539264   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.181  rustc            539277 539276   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.190  rustc            539292 539264   0 /home/xmoe/.cargo/bin/rustc -vV\n20.205  rustc            539304 539276   0 /home/xmoe/.cargo/bin/rustc -vV\n20.213  rustc            539304 539276   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.226  cross            539315 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n20.227  rustc            539318 539315   0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.228  cargo            539319 539276   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.239  rustc            539318 539315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.242  cargo            539319 539276   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.257  rustc            539339 539315   0 /home/xmoe/.cargo/bin/rustc -vV\n20.261  rustc            539340 539319   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.269  rustc            539292 539264   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.275  rustc            539339 539315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.282  rustc            539350 539319   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.289  cargo            539352 539264   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.293  cargo            539354 539315   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n20.299  cargo            539352 539264   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.303  rustc            539368 539319   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.319  rustc            539378 539352   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.319  cargo            539354 539315   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n20.331  rustc            539381 539354   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.332  rustc            539382 539352   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.343  rustc            539384 539354   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.354  rustc            539388 539352   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.365  rustc            539395 539354   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.390  rustc            539402 539276   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n20.397  rustc            539402 539276   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n20.412  containerd-shim  539416 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f82cb79421275c0a2277f2bea92e76ce3b69ae69348bbff53d6f7fb93321cfa7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f82cb79421275c0a2277f2bea92e76ce3b69ae69348bbff53d6f7fb9332 delete\n20.420  runc             539424 539416   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f82cb79421275c0a2277f2bea92e76ce3b69ae69348bbff53d6f7fb93321cfa --log-format json delete --force f82cb79421275c0a2277f2bea92e76ce3b69ae69348bbff53d6f7fb93321cfa7\n20.426  rustc            539429 539264   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n20.437  rustc            539429 539264   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n20.456  docker           539444 539264   0 /usr/bin/docker --help\n20.483  docker           539453 539264   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n20.487  systemd-sysctl   539459 539089   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2e612e7 --prefix=/net/ipv4/neigh/veth2e612e7 --prefix=/net/ipv6/conf/veth2e612e7 --prefix=/net/ipv6/neigh/veth2e612e7\n20.529  docker           539467 539276   0 /usr/bin/docker --help\n20.540  runc             539474 1599     0 /usr/bin/runc --version\n20.546  docker-init      539485 1599     0 /usr/bin/docker-init --version\n20.549  docker           539486 539264   0 /usr/bin/docker info -f {{.SecurityOptions}}\n20.579  runc             539495 1599     0 /usr/bin/runc --version\n20.584  rustup           539501 522103   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n20.586  docker-init      539502 1599     0 /usr/bin/docker-init --version\n20.628  rustup           539515 539264   0 /home/xmoe/.cargo/bin/rustup toolchain list\n20.641  rustup           539524 539264   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n20.655  docker           539534 539276   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n20.675  runc             539543 1599     0 /usr/bin/runc --version\n20.681  docker-init      539549 1599     0 /usr/bin/docker-init --version\n20.685  docker           539551 539276   0 /usr/bin/docker info -f {{.SecurityOptions}}\n20.687  rustup           539552 539264   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n20.696  rustc            539566 539354   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.717  runc             539572 1599     0 /usr/bin/runc --version\n20.722  docker-init      539578 1599     0 /usr/bin/docker-init --version\n20.744  uname            539581 539264   0 /usr/bin/uname -r\n20.769  rustup           539586 539276   0 /home/xmoe/.cargo/bin/rustup toolchain list\n20.779  rustup           539596 539276   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n20.783  docker           539597 539264   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n20.789  rustc            539584 527474   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name sctk_adwaita --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/sctk-adwaita-0.8.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"ab_glyph\" --cfg feature=\"memmap2\" --check-cfg cfg(docsrs,test) ...\n20.839  rustup           539623 539276   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n20.882  uname            539634 539276   0 /usr/bin/uname -r\n20.897  rustc            539635 539315   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n"
    },
    {
      "argv": [
        "/target/debug/build/ittapi-sys-153a64372a747f59/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 536092,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/ittapi-sys-153a64372a747f59/build-script-build",
      "pid": 536092,
      "ppid": 535231,
      "root_cargo_pid": 535231,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [],
      "build_script_related": true,
      "build_script_root_pid": 536092,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "powerpc64le-lin",
      "pid": 536099,
      "ppid": 536092,
      "root_cargo_pid": 535231,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-E",
        "-quiet",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/8161832041459257609detect_compiler_family.c",
        "-msecure-plt",
        "-mcpu=power8",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 536092,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 536100,
      "ppid": 536099,
      "root_cargo_pid": 535231,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 536092,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 536114,
      "ppid": 536092,
      "root_cargo_pid": 535231,
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
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "c-library/src/ittnotify/",
        "-I",
        "c-library/include/",
        "-Wall",
        "-Wextra",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-ittnotify_static.o",
        "-c",
        "c-library/src/ittnotify/ittnotify_static.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 536092,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 536123,
      "ppid": 536092,
      "root_cargo_pid": 535231,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "c-library/src/ittnotify/",
        "-I",
        "c-library/include/",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "c-library/src/ittnotify/ittnotify_static.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "ittnotify_static.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-ittnotify_static.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 536092,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 536136,
      "ppid": 536123,
      "root_cargo_pid": 535231,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "c-library/src/ittnotify/",
        "-I",
        "c-library/include/",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-ittnotify_static.o",
        "/tmp/cc1VdPKi.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 536092,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 536400,
      "ppid": 536123,
      "root_cargo_pid": 535231,
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
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "c-library/src/ittnotify/",
        "-I",
        "c-library/include/",
        "-Wall",
        "-Wextra",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-jitprofiling.o",
        "-c",
        "c-library/src/ittnotify/jitprofiling.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 536092,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 536414,
      "ppid": 536092,
      "root_cargo_pid": 535231,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "c-library/src/ittnotify/",
        "-I",
        "c-library/include/",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "c-library/src/ittnotify/jitprofiling.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "jitprofiling.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-jitprofiling.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 536092,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 536416,
      "ppid": 536414,
      "root_cargo_pid": 535231,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "c-library/src/ittnotify/",
        "-I",
        "c-library/include/",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-jitprofiling.o",
        "/tmp/ccDXE7wk.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 536092,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 536431,
      "ppid": 536414,
      "root_cargo_pid": 535231,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "cqD",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/libittnotify.a",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-ittnotify_static.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-jitprofiling.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 536092,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 536443,
      "ppid": 536092,
      "root_cargo_pid": 535231,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "sD",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/libittnotify.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 536092,
      "build_script_target_dir": "ittapi-sys-153a64372a747f59",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 536450,
      "ppid": 536092,
      "root_cargo_pid": 535231,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "ittapi-sys",
      "cwd": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "event_id": "bsrun:96e9f481375da5c2:cda8081d828c41f0:f2ef5110e3cd48e0",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/ittapi-sys-153a64372a747f59/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
      "out_dir": "/target/debug/build/ittapi-sys-153a64372a747f59/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
      "success": true,
      "target": null,
      "version": "0.4.0",
      "_owner": {
        "crate": "ittapi-sys",
        "version": "0.4.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0#ittapi-sys@0.4.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0",
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
