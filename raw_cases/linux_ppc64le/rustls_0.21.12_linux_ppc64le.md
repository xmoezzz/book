# `rustls` `0.21.12`

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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
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
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8",
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
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-51188-1783992783891210956.map",
  "pid": 51188,
  "ppid": 51110,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-51188-1783992783891210956.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
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
  "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "workspace_root": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.3",
      "name": "aho-corasick",
      "version": "1.1.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#base64@0.21.7",
      "name": "base64",
      "version": "0.21.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/base64-0.21.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/base64-0.21.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bencher@0.1.5",
      "name": "bencher",
      "version": "0.1.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bencher-0.1.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bencher-0.1.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.95",
      "name": "cc",
      "version": "1.0.95",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.95/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.95"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
      "name": "cfg-if",
      "version": "1.0.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#env_logger@0.10.2",
      "name": "env_logger",
      "version": "0.10.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/env_logger-0.10.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/env_logger-0.10.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.2.14",
      "name": "getrandom",
      "version": "0.2.14",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.14/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.14"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#hermit-abi@0.3.9",
      "name": "hermit-abi",
      "version": "0.3.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.3.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.3.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#humantime@2.1.0",
      "name": "humantime",
      "version": "2.1.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/humantime-2.1.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/humantime-2.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#is-terminal@0.4.12",
      "name": "is-terminal",
      "version": "0.4.12",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/is-terminal-0.4.12/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/is-terminal-0.4.12"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
      "name": "libc",
      "version": "0.2.153",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.21",
      "name": "log",
      "version": "0.4.21",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.21/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.21"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.2",
      "name": "memchr",
      "version": "2.7.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.10.4",
      "name": "regex",
      "version": "1.10.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.10.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.10.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.6",
      "name": "regex-automata",
      "version": "0.4.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.3",
      "name": "regex-syntax",
      "version": "0.8.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
      "name": "ring",
      "version": "0.17.8",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8"
    },
    {
      "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
      "name": "rustls",
      "version": "0.21.12",
      "manifest_path": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustls-pemfile@1.0.4",
      "name": "rustls-pemfile",
      "version": "1.0.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustls-pemfile-1.0.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustls-pemfile-1.0.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustls-webpki@0.101.7",
      "name": "rustls-webpki",
      "version": "0.101.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustls-webpki-0.101.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustls-webpki-0.101.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#sct@0.7.1",
      "name": "sct",
      "version": "0.7.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/sct-0.7.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/sct-0.7.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#spin@0.9.8",
      "name": "spin",
      "version": "0.9.8",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/spin-0.9.8/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/spin-0.9.8"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#termcolor@1.4.1",
      "name": "termcolor",
      "version": "1.4.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#untrusted@0.9.0",
      "name": "untrusted",
      "version": "0.9.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/untrusted-0.9.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/untrusted-0.9.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.11.0+wasi-snapshot-preview1",
      "name": "wasi",
      "version": "0.11.0+wasi-snapshot-preview1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.0+wasi-snapshot-preview1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.0+wasi-snapshot-preview1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#webpki-roots@0.25.4",
      "name": "webpki-roots",
      "version": "0.25.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/webpki-roots-0.25.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/webpki-roots-0.25.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.8",
      "name": "winapi-util",
      "version": "0.1.8",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.8/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.8"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.52.0",
      "name": "windows-sys",
      "version": "0.52.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.52.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.52.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.52.5",
      "name": "windows-targets",
      "version": "0.52.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.52.5",
      "name": "windows_aarch64_gnullvm",
      "version": "0.52.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.52.5",
      "name": "windows_aarch64_msvc",
      "version": "0.52.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.52.5",
      "name": "windows_i686_gnu",
      "version": "0.52.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnullvm@0.52.5",
      "name": "windows_i686_gnullvm",
      "version": "0.52.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnullvm-0.52.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnullvm-0.52.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.52.5",
      "name": "windows_i686_msvc",
      "version": "0.52.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.52.5",
      "name": "windows_x86_64_gnu",
      "version": "0.52.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.52.5",
      "name": "windows_x86_64_gnullvm",
      "version": "0.52.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.5",
      "name": "windows_x86_64_msvc",
      "version": "0.52.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.5"
    }
  ],
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "exit_code": 0,
  "kind": "exec",
  "pid": 51188,
  "ppid": 51110,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rustls",
  "cargo_pkg_version": "0.21.12",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "event_id": "used:cc:7b3816f9d77727d6:3cc7127cb83a9aa0:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
  "pid": 51188,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rustls",
  "cargo_pkg_version": "0.21.12",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "event_id": "used:cc:7b3816f9d77727d6:24aaf905568abeeb:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
  "pid": 51188,
  "sha256": "b9857273de0f0eb6790f4bcddeb10e4bdf58d7884145fa18844ac18b87b010a0",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rustls",
  "cargo_pkg_version": "0.21.12",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "event_id": "used:cc:7b3816f9d77727d6:1659140dd49f7bf6:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
  "pid": 51188,
  "sha256": "b93ad444dcce8804c7b36e41be48e297f3f75aec602915da266de464042a864a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rustls",
  "cargo_pkg_version": "0.21.12",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "event_id": "used:cc:7b3816f9d77727d6:403fdecfd9e88adb:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
  "pid": 51188,
  "sha256": "e16192e82a6a55409bb0ddeef9ecb826a2a1e726b5d774e19517a36fdc2c80e3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rustls",
  "cargo_pkg_version": "0.21.12",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "event_id": "used:cc:7b3816f9d77727d6:0f40e438d5159b12:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
  "pid": 51188,
  "sha256": "a322b0c5d63af985eb903640674e12de9b6a791f9ddeae6e96a64138b759f000",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rustls",
  "cargo_pkg_version": "0.21.12",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "event_id": "used:cc:7b3816f9d77727d6:79ee593c0724e8a2:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
  "pid": 51188,
  "sha256": "466bf857385651585270a3062a18deff4adad60e1d93c4cf765ef7f15822c7a9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rustls",
  "cargo_pkg_version": "0.21.12",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "event_id": "used:cc:7b3816f9d77727d6:9c44d4c80b5dfb72:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
  "pid": 51188,
  "sha256": "2a6cf24c0a0269e4833fdfcff9cd095c0e58be7a7e310e83ace955edb2ba5340",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
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
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "cargo_pkg_name": "rustls",
  "cargo_pkg_version": "0.21.12",
  "context_path": "/tmp/native-trace-50171-1783992780090/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-50171-1783992780090/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 51188,
  "ppid": 51110,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8",
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
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-51188-1783992783891210956.map",
  "pid": 51188,
  "ppid": 51110,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-51188-1783992783891210956.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "exit_code": 0,
  "kind": "exec",
  "pid": 51463,
  "ppid": 51102,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.153",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "event_id": "used:cc:b47364ada97c6bc2:d2e7d9c14f456d4c:6abd7aadaee76ef4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
  "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
  "pid": 51463,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.153",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "event_id": "used:cc:b47364ada97c6bc2:8fbc204c2de40ae3:6abd7aadaee76ef4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
  "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
  "pid": 51463,
  "sha256": "1c1bda37289ec1d821d844082238c8264f2503ddb9285e4c4b35874be718b5b0",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 16

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.153",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "event_id": "used:cc:b47364ada97c6bc2:8fa1e6b2f28555cd:6abd7aadaee76ef4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
  "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
  "pid": 51463,
  "sha256": "5e70191dfb043a5385388b604c5c1feba8fec2b44fdb25873028a427923b8d6a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 17

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.153",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "event_id": "used:cc:b47364ada97c6bc2:56ea4f27c87e1fc7:6abd7aadaee76ef4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
  "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
  "pid": 51463,
  "sha256": "8197d6a77e8ee592aad69945794d29560ea22f5d99de7fd4a19d8a5ec3c53dd4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 18

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.153",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "event_id": "used:cc:b47364ada97c6bc2:6ef887c52156788c:6abd7aadaee76ef4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
  "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
  "pid": 51463,
  "sha256": "9f762bbe468a79bebb41c2e60a430efa1e822b7c5745db8269c41350de4cf6f5",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 19

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/raw-dylibs",
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
  "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 20

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.153",
  "context_path": "/tmp/native-trace-50171-1783992780090/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-50171-1783992780090/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 51463,
  "ppid": 51102,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 21

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4",
    "/target/debug/build/libc-c3c858474dcfa7e6",
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
      "directory": "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4",
      "kind": "object",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-c3c858474dcfa7e6",
      "kind": "object",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-c3c858474dcfa7e6",
      "kind": "object",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-c3c858474dcfa7e6",
      "kind": "object",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-c3c858474dcfa7e6",
      "kind": "object",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-51463-1783992784204685603.map",
  "pid": 51463,
  "ppid": 51102,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-51463-1783992784204685603.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 22

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "exit_code": 0,
  "kind": "exec",
  "pid": 52402,
  "ppid": 52351,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 23

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ring",
  "cargo_pkg_version": "0.17.8",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "event_id": "used:cc:d3ed579287892b7b:79161489f646a2f5:0983853cb5c6903e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
  "path": "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
  "pid": 52402,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 24

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ring",
  "cargo_pkg_version": "0.17.8",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "event_id": "used:cc:d3ed579287892b7b:bf7722017c206f9e:0983853cb5c6903e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
  "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
  "pid": 52402,
  "sha256": "025527fb46fcb2d3fc121ee840b5e1003a1d506b6ad7cda5c827f0415c6617e3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 25

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ring",
  "cargo_pkg_version": "0.17.8",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "event_id": "used:cc:d3ed579287892b7b:29db5b508b5dac78:0983853cb5c6903e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
  "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
  "pid": 52402,
  "sha256": "b8d0e2f4da86f4e5439d83c7aedf252d0395627a3a4070292812a2e95453eab1",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 26

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ring",
  "cargo_pkg_version": "0.17.8",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "event_id": "used:cc:d3ed579287892b7b:750b69807bdb0049:0983853cb5c6903e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
  "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
  "pid": 52402,
  "sha256": "1473c60f65c2830cec9ad1acc6f763ed7f8bbed33d8426cb25651a2190e4f471",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 27

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "ring",
  "cargo_pkg_version": "0.17.8",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "event_id": "used:cc:d3ed579287892b7b:349090cbd640d504:0983853cb5c6903e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
  "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
  "pid": 52402,
  "sha256": "ef84c5450bab83b8ef3f7972151a3ee714a0a4b83e5707bb18cab99aff3090fb",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 28

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/raw-dylibs",
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
  "output": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 29

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "cargo_pkg_name": "ring",
  "cargo_pkg_version": "0.17.8",
  "context_path": "/tmp/native-trace-50171-1783992780090/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-50171-1783992780090/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 52402,
  "ppid": 52351,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 30

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV",
    "/target/debug/build/ring-36133a68ed4b831a",
    "/target/debug/deps",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "/lib/x86_64-linux-gnu",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55740            55740        c    16         /target/debug/build/ring-36133a68ed4b831a",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55750            55750        c    16         /target/debug/build/ring-36133a68ed4b831a",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/598d0            598d0        c    16         /target/debug/build/ring-36133a68ed4b831a",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/637b0            637b0        9    16         /target/debug/build/ring-36133a68ed4b831a",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/637c0            637c0        9    16         /target/debug/build/ring-36133a68ed4b831a"
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
      "directory": "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV",
      "kind": "object",
      "path": "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ring-36133a68ed4b831a",
      "kind": "object",
      "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ring-36133a68ed4b831a",
      "kind": "object",
      "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ring-36133a68ed4b831a",
      "kind": "object",
      "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/ring-36133a68ed4b831a",
      "kind": "object",
      "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.00.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.02.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.03.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.04.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.05.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.01.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.06.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.07.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.08.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.09.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.10.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.11.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.12.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.13.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.14.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.15.rcgu.o",
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
    },
    {
      "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55740            55740        c    16         /target/debug/build/ring-36133a68ed4b831a",
      "kind": "dynamic_library",
      "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55740            55740        c    16         /target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN102_$LT$core..iter..adapters..filter..Filter$LT$I$C$P$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h366b1fdc5249421eE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/build/ring-36133a68ed4b831a",
      "kind": "dynamic_library",
      "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN102_$LT$core..iter..adapters..filter..Filter$LT$I$C$P$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h366b1fdc5249421eE",
      "source": "link_map"
    },
    {
      "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55750            55750        c    16         /target/debug/build/ring-36133a68ed4b831a",
      "kind": "dynamic_library",
      "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55750            55750        c    16         /target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN102_$LT$core..iter..adapters..filter..Filter$LT$I$C$P$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17hdd043471a900c196E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/build/ring-36133a68ed4b831a",
      "kind": "dynamic_library",
      "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN102_$LT$core..iter..adapters..filter..Filter$LT$I$C$P$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17hdd043471a900c196E",
      "source": "link_map"
    },
    {
      "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/598d0            598d0        c    16         /target/debug/build/ring-36133a68ed4b831a",
      "kind": "dynamic_library",
      "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/598d0            598d0        c    16         /target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h522cca2806a5a384E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/build/ring-36133a68ed4b831a",
      "kind": "dynamic_library",
      "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h522cca2806a5a384E",
      "source": "link_map"
    },
    {
      "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/637b0            637b0        9    16         /target/debug/build/ring-36133a68ed4b831a",
      "kind": "dynamic_library",
      "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/637b0            637b0        9    16         /target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o:(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h3c3f8f1374e45b16E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/build/ring-36133a68ed4b831a",
      "kind": "dynamic_library",
      "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o:(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h3c3f8f1374e45b16E",
      "source": "link_map"
    },
    {
      "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/637c0            637c0        9    16         /target/debug/build/ring-36133a68ed4b831a",
      "kind": "dynamic_library",
      "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/637c0            637c0        9    16         /target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o:(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h5f762ba4a5828b0bE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/build/ring-36133a68ed4b831a",
      "kind": "dynamic_library",
      "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o:(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h5f762ba4a5828b0bE",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "/tmp/native-trace-link-cc-52402-1783992785697521466.map",
  "pid": 52402,
  "ppid": 52351,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-52402-1783992785697521466.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 31

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

#### Record 32

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 1,
  "parsed_event_count": 894,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 895,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": " 1 --filter-platform aarch64-unknown-linux-gnu\n17.725  runc             54622  49060    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892b --log-format json --systemd-cgroup kill --all 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a 9\n17.734  runc             54628  49060    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892b --log-format json --systemd-cgroup delete 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a\n17.739  cargo            54606  54542    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n17.750  runc             54634  54537    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc031 --log-format json --systemd-cgroup start 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0\n17.754  rustc            54640  54606    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.757  sh               54570  54537    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.758  cargo            54641  54570    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.767  rustc            54643  54606    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.772  cargo-native-tr  54641  54570    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.777  cargo            54645  54641    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.782  rustc            54648  54606    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.792  rustc            54651  54645    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.804  rustc            54654  54645    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.822  rustc            54658  54542    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.845  rustc            54658  54542    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.856  docker           54670  54542    0 /usr/bin/docker --help\n17.861  execsnoop        54676  54641    0 /usr/local/bin/execsnoop -t\n17.861  python3          54676  54641    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.869  docker           54687  54542    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.880  runc             54696  46492    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f49 --log-format json --systemd-cgroup kill --all a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922 9\n17.880  runc             54697  1599     0 /usr/bin/runc --version\n17.883  docker-init      54708  1599     0 /usr/bin/docker-init --version\n17.884  docker           54709  54542    0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.887  runc             54715  46492    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f49 --log-format json --systemd-cgroup delete a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922\n17.896  runc             54726  1599     0 /usr/bin/runc --version\n17.899  docker-init      54732  1599     0 /usr/bin/docker-init --version\n17.919  rustup           54733  54542    0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.933  containerd-shim  54743  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892b delete\n17.935  runc             54750  54743    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9 --log-format json delete --force 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a\n17.942  rustup           54755  54542    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.966  rustup           54764  54542    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.966  systemd-sysctl   54765  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe425dec --prefix=/net/ipv4/neigh/vethe425dec --prefix=/net/ipv6/conf/vethe425dec --prefix=/net/ipv6/neigh/vethe425dec\n17.990  uname            54774  54542    0 /usr/bin/uname -r\n18.007  docker           54775  54542    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n18.044  systemd-sysctl   54789  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth76e10a3 --prefix=/net/ipv4/neigh/veth76e10a3 --prefix=/net/ipv6/conf/veth76e10a3 --prefix=/net/ipv6/neigh/veth76e10a3\n18.044  systemd-sysctl   54788  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf2069ec --prefix=/net/ipv4/neigh/vethf2069ec --prefix=/net/ipv6/conf/vethf2069ec --prefix=/net/ipv6/neigh/vethf2069ec\n18.059  containerd-shim  54791  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 start\n18.062  containerd-shim  54798  54791    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 -address /var/run/docker/containerd/containerd.sock\n18.066  runc             54808  54798    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10\n18.067  containerd-shim  54811  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f49 delete\n18.069  runc             54820  54811    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f495792 --log-format json delete --force a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922\n18.071  exe              54827  54808    0 /proc/self/exe init\n18.106  systemd-sysctl   54832  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7f2e47d --prefix=/net/ipv4/neigh/veth7f2e47d --prefix=/net/ipv6/conf/veth7f2e47d --prefix=/net/ipv6/neigh/veth7f2e47d\n18.121  exe              54838  54808    0 /proc/1599/exe -exec-root=/var/run/docker 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 d7da31e8f8e1\n18.140  exe              54846  1599     0 /proc/self/exe /var/run/docker/netns/3e401da5d4b2 all false\n18.200  runc             54864  54798    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --log-format json --systemd-cgroup start 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10\n18.205  sh               54831  54798    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n18.206  cargo            54870  54831    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n18.217  cargo-native-tr  54870  54831    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n18.220  cargo            54871  54870    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n18.230  rustc            54872  54871    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.242  rustc            54874  54871    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n18.251  runc             54878  49386    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b --log-format json --systemd-cgroup kill --all bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888 9\n18.268  runc             54885  49386    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b --log-format json --systemd-cgroup delete bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888\n18.280  execsnoop        54891  54870    0 /usr/local/bin/execsnoop -t\n18.280  python3          54891  54870    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n18.294  runc             54894  49353    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 --log-format json --systemd-cgroup kill --all a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7 9\n18.312  runc             54901  49353    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 --log-format json --systemd-cgroup delete a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7\n18.489  containerd-shim  54907  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b delete\n18.491  runc             54914  54907    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf788 --log-format json delete --force bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888\n18.528  systemd-sysctl   54919  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethfb8276c --prefix=/net/ipv4/neigh/vethfb8276c --prefix=/net/ipv6/conf/vethfb8276c --prefix=/net/ipv6/neigh/vethfb8276c\n18.536  containerd-shim  54921  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 delete\n18.538  runc             54928  54921    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f --log-format json delete --force a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7\n18.581  systemd-sysctl   54933  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth651aca6 --prefix=/net/ipv4/neigh/veth651aca6 --prefix=/net/ipv6/conf/veth651aca6 --prefix=/net/ipv6/neigh/veth651aca6\n18.648  runc             54934  49256    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 --log-format json --systemd-cgroup kill --all f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96 9\n18.664  runc             54940  49256    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 --log-format json --systemd-cgroup delete f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96\n18.845  containerd-shim  54946  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 delete\n18.848  runc             54953  54946    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da9 --log-format json delete --force f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96\n18.885  systemd-sysctl   54959  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd600a16 --prefix=/net/ipv4/neigh/vethd600a16 --prefix=/net/ipv6/conf/vethd600a16 --prefix=/net/ipv6/neigh/vethd600a16\n18.953  runc             54961  49929    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d --log-format json --systemd-cgroup kill --all 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637 9\n18.960  runc             54967  49929    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d --log-format json --systemd-cgroup delete 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637\n19.139  containerd-shim  54974  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d delete\n19.142  runc             54981  54974    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d9863 --log-format json delete --force 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637\n19.177  systemd-sysctl   54986  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5b8f709 --prefix=/net/ipv4/neigh/veth5b8f709 --prefix=/net/ipv6/conf/veth5b8f709 --prefix=/net/ipv6/neigh/veth5b8f709\n19.288  sh               54987  2147557   0 /bin/sh -c which ps\n19.289  which            54987  2147557   0 /usr/bin/which ps\n19.291  sh               54988  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n19.292  ps               54988  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n19.317  sh               54989  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n19.318  cpuUsage.sh      54989  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n19.319  sed              54990  54989    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n19.321  cat              54991  54989    0 /usr/bin/cat /proc/2240539/stat\n19.322  cat              54992  54989    0 /usr/bin/cat /proc/4193716/stat\n19.323  sleep            54993  54989    0 /usr/bin/sleep 1\n19.716  cargo            54994  54641    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n19.729  rustc            54995  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n19.758  rustc            55001  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n19.798  cc               55024  55001    0 /tmp/native-trace-54641-1783992801298/shims/cc -m64 /target/debug/build/valuable-0ca3a52e87f47781/rustcum31Fu/symbols.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2bcuvqydoknozqmp1me20ruil.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2hvolwvrh1z7h0esed9fdlkq6.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2ydqatcbwpyv0nfser2rvjw0s.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.320kk89i2c31bqlrt1pe5ftwu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.3dorb0xb6tyxiuzsrh06fg7wn.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.44p8ua3isbvp2so96dfqsrcv0.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.4mgnn3dy9r06fb4dhef909zhp.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54olwytbg728sxv8s6jzea9ac.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54xlj1thl6ekctt4ryak72mpk.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5gyye0zaqcjlw0qa72458hp4p.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5m686vmv93io6lluiiyhiylju.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.7d19io80brmbzee20rw5urjmi.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.b7inlg8jykc014dunu01jjkqu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.c3a0y0h3kjig5bmjwukot6pmm.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.deexadt1dri1ihovsh8z1lp29.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.dlbacscotl41na11230m8gkv8.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.e0jqet5ubfmmb5vnbm2c21wdk.15hdgiv.rcgu.o ...\n19.799  cc               55025  55024    0 /usr/bin/cc -m64 /target/debug/build/valuable-0ca3a52e87f47781/rustcum31Fu/symbols.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2bcuvqydoknozqmp1me20ruil.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2hvolwvrh1z7h0esed9fdlkq6.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2ydqatcbwpyv0nfser2rvjw0s.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.320kk89i2c31bqlrt1pe5ftwu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.3dorb0xb6tyxiuzsrh06fg7wn.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.44p8ua3isbvp2so96dfqsrcv0.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.4mgnn3dy9r06fb4dhef909zhp.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54olwytbg728sxv8s6jzea9ac.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54xlj1thl6ekctt4ryak72mpk.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5gyye0zaqcjlw0qa72458hp4p.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5m686vmv93io6lluiiyhiylju.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.7d19io80brmbzee20rw5urjmi.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.b7inlg8jykc014dunu01jjkqu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.c3a0y0h3kjig5bmjwukot6pmm.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.deexadt1dri1ihovsh8z1lp29.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.dlbacscotl41na11230m8gkv8.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.e0jqet5ubfmmb5vnbm2c21wdk.15hdgiv.rcgu.o ...\n19.802  collect2         55026  55025    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.803  ld.lld           55027  55026    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781 ...\n19.804  rust-lld         55027  55026    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.842  build-script-bu  55045  54994    0 /target/debug/build/valuable-0ca3a52e87f47781/build-script-build\n19.846  rustc            55047  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name valuable --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n20.126  cargo            55059  54870    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n20.138  rustc            55070  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.164  rustc            55113  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n20.164  rustc            55111  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.18/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=ba1b82e103e0280b ...\n20.263  cc               55188  55113    0 /tmp/native-trace-54870-1783992801742/shims/cc -m64 /target/debug/build/proc-macro2-46239aad0aaf2dde/rustcz8FJmv/symbols.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0bv3et31ep2k9sd4r4xv6yltt.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0edhhq7oafgl2yf0nrxumcg9r.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0g0902jm3uya6wioho7beok0j.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0owef7ksnbk6ukcc2242nefkr.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0rdzizyhqamtksvgo7enpq5az.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1r69zij4wcxunk2gd17a0kpg6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1sghvgwc08k4idxie37yo3pw0.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1wbfjtyvleo9dhvql6dw9ezks.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2om80ctxk1ydfs1240ujhhg0b.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2ylb2sbb9n609gy1nl3eivm1m.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.34jg2bcz8z6kfpvajxful9pig.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3dgkawms7tf7icnefiv8uh2ur.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3h5kxyomdhio13fti327b3ul4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3pfht32bkan9uc6xs96laffv6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3vy5vc4kvl4zobt41ffusuic4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3wfb4bv7o9ei3djc1ma3hgool.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.4sen9su2ywavj025286hzh4rs.0uq14k2.rcgu.o ...\n20.264  cc               55189  55188    0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-46239aad0aaf2dde/rustcz8FJmv/symbols.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0bv3et31ep2k9sd4r4xv6yltt.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0edhhq7oafgl2yf0nrxumcg9r.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0g0902jm3uya6wioho7beok0j.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0owef7ksnbk6ukcc2242nefkr.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0rdzizyhqamtksvgo7enpq5az.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1r69zij4wcxunk2gd17a0kpg6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1sghvgwc08k4idxie37yo3pw0.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1wbfjtyvleo9dhvql6dw9ezks.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2om80ctxk1ydfs1240ujhhg0b.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2ylb2sbb9n609gy1nl3eivm1m.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.34jg2bcz8z6kfpvajxful9pig.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3dgkawms7tf7icnefiv8uh2ur.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3h5kxyomdhio13fti327b3ul4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3pfht32bkan9uc6xs96laffv6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3vy5vc4kvl4zobt41ffusuic4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3wfb4bv7o9ei3djc1ma3hgool.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.4sen9su2ywavj025286hzh4rs.0uq14k2.rcgu.o ...\n20.267  collect2         55190  55189    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n20.269  ld.lld           55191  55190    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde ...\n20.270  rust-lld         55191  55190    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n20.325  sed              55209  54989    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n20.325  build-script-bu  55210  55059    0 /target/debug/build/proc-macro2-46239aad0aaf2dde/build-script-build\n20.326  cat              55211  54989    0 /usr/bin/cat /proc/2240539/stat\n20.327  rustc            55212  55210    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n20.328  cat              55214  54989    0 /usr/bin/cat /proc/4193716/stat\n20.337  rustc            55217  55210    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-1a2ad12dc9160ce7/out/probe build/probe.rs --target aarch64-unknown-linux-gnu\n20.364  rustc            55222  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n20.929  cross            55331  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.930  rustc            55334  55331    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.951  rustc            55334  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.963  rustc            55346  55331    0 /home/xmoe/.cargo/bin/rustc -vV\n20.984  rustc            55346  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.994  cargo            55356  55331    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.015  cargo            55356  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.026  rustc            55366  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.028  git              55365  2235138   0 /usr/bin/git config --get commit.template\n21.035  rustc            55368  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.043  git              55369  2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n21.046  rustc            55373  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.059  git              55374  2235138   0 /usr/bin/git status -z -uall\n21.071  rustc            55379  55331    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n21.074  git              55378  2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n21.093  rustc            55379  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n21.104  docker           55391  55331    0 /usr/bin/docker --help\n21.116  docker           55402  55331    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n21.128  runc             55412  1599     0 /usr/bin/runc --version\n21.131  docker-init      55418  1599     0 /usr/bin/docker-init --version\n21.132  docker           55419  55331    0 /usr/bin/docker info -f {{.SecurityOptions}}\n21.142  runc             55430  1599     0 /usr/bin/runc --version\n21.146  docker-init      55436  1599     0 /usr/bin/docker-init --version\n21.166  rustup           55440  55331    0 /home/xmoe/.cargo/bin/rustup toolchain list\n21.188  rustup           55449  55331    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n21.209  rustup           55458  55331    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n21.233  uname            55467  55331    0 /usr/bin/uname -r\n21.248  docker           55468  55331    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n21.284  systemd-sysctl   55483  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8170368 --prefix=/net/ipv4/neigh/veth8170368 --prefix=/net/ipv6/conf/veth8170368 --prefix=/net/ipv6/neigh/veth8170368\n21.284  systemd-sysctl   55482  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth81dd9a9 --prefix=/net/ipv4/neigh/veth81dd9a9 --prefix=/net/ipv6/conf/veth81dd9a9 --prefix=/net/ipv6/neigh/veth81dd9a9\n21.297  containerd-shim  55484  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 start\n21.300  containerd-shim  55491  55484    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 -address /var/run/docker/containerd/containerd.sock\n21.304  runc             55501  55491    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956\n21.309  exe              55509  55501    0 /proc/self/exe init\n21.327  cross            55513  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n21.328  rustc            55520  55513    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.333  rustc            55520  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.342  exe              55532  55501    0 /proc/1599/exe -exec-root=/var/run/docker 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 d7da31e8f8e1\n21.344  rustc            55539  55513    0 /home/xmoe/.cargo/bin/rustc -vV\n21.349  rustc            55539  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.355  cross            55549  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n21.356  rustc            55552  55549    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.359  cargo            55561  55513    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n21.359  cross            55564  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n21.361  rustc            55567  55564    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.362  exe              55576  1599     0 /proc/self/exe /var/run/docker/netns/8b628a44607d all false\n21.364  cargo            55561  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n21.365  rustc            55567  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.374  rustc            55596  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.377  rustc            55597  55564    0 /home/xmoe/.cargo/bin/rustc -vV\n21.382  rustc            55552  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.383  rustc            55597  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.384  rustc            55607  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.391  cargo            55614  55564    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.393  rustc            55616  55549    0 /home/xmoe/.cargo/bin/rustc -vV\n21.394  rustc            55625  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.396  cargo            55614  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.407  rustc            55637  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.409  runc             55639  55491    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --log-format json --systemd-cgroup start 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956\n21.414  sh               55511  55491    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n21.415  cargo            55646  55511    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n21.416  rustc            55647  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.419  rustc            55616  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.427  cargo-native-tr  55646  55511    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n21.428  cargo            55652  55549    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n21.429  rustc            55653  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.431  cargo            55654  55646    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n21.441  rustc            55666  55654    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.450  cargo            55652  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n21.453  rustc            55668  55654    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.460  rustc            55670  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.469  rustc            55674  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.482  rustc            55678  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.518  git              55683  2235138   0 /usr/bin/git worktree list --porcelain\n21.556  cross            55684  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n21.557  rustc            55687  55684    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.561  rustc            55687  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.573  runc             55701  47737    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a --log-format json --systemd-cgroup kill --all 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9 9\n21.573  rustc            55700  55684    0 /home/xmoe/.cargo/bin/rustc -vV\n21.578  rustc            55700  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.587  cargo            55716  55684    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.590  runc             55725  47737    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a --log-format json --systemd-cgroup delete 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9\n21.591  cargo            55716  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.601  rustc            55731  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.611  rustc            55733  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.634  rustc            55737  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.719  runc             55741  49799    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e --log-format json --systemd-cgroup kill --all f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e 9\n21.726  runc             55748  49799    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e --log-format json --systemd-cgroup delete f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e\n21.806  containerd-shim  55754  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a delete\n21.808  runc             55761  55754    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a --log-format json delete --force 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9\n21.811  runc             55767  50023    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc --log-format json --systemd-cgroup kill --all a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0 9\n21.827  runc             55773  50023    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc --log-format json --systemd-cgroup delete a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0\n21.850  systemd-sysctl   55779  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethae76c09 --prefix=/net/ipv4/neigh/vethae76c09 --prefix=/net/ipv6/conf/vethae76c09 --prefix=/net/ipv6/neigh/vethae76c09\n21.913  runc             55780  50289    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d67 --log-format json --systemd-cgroup kill --all 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb 9\n21.930  runc             55786  50289    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d67 --log-format json --systemd-cgroup delete 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb\n21.961  cross            55792  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n21.963  rustc            55795  55792    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.968  rustc            55795  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.979  rustc            55807  55792    0 /home/xmoe/.cargo/bin/rustc -vV\n21.984  rustc            55807  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.986  containerd-shim  55816  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e delete\n21.989  runc             55822  55816    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1 --log-format json delete --force f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e\n21.991  cross            55829  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n21.992  rustc            55832  55829    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.993  cargo            55833  55792    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.997  rustc            55832  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.997  cargo            55833  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n22.007  rustc            55853  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.009  rustc            55854  55829    0 /home/xmoe/.cargo/bin/rustc -vV\n22.014  rustc            55854  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.016  rustc            55864  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n22.023  cargo            55869  55829    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n22.025  systemd-sysctl   55870  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethddd6c57 --prefix=/net/ipv4/neigh/vethddd6c57 --prefix=/net/ipv6/conf/vethddd6c57 --prefix=/net/ipv6/neigh/vethddd6c57\n22.026  containerd-shim  55880  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc delete\n22.028  rustc            55884  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n22.028  cargo            55869  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n22.029  runc             55887  55880    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f --log-format json delete --force a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0\n22.038  rustc            55896  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.047  rustc            55898  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n22.059  rustc            55902  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n22.066  systemd-sysctl   55903  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf192d49 --prefix=/net/ipv4/neigh/vethf192d49 --prefix=/net/ipv6/conf/vethf192d49 --prefix=/net/ipv6/neigh/vethf192d49\n22.154  containerd-shim  55908  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d67 delete\n22.156  runc             55915  55908    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7c --log-format json delete --force 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb\n22.187  systemd-sysctl   55920  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7b4cddd --prefix=/net/ipv4/neigh/veth7b4cddd --prefix=/net/ipv6/conf/veth7b4cddd --prefix=/net/ipv6/neigh/veth7b4cddd\n23.325  rustc            55925  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.374  rustc            55927  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.401  rustc            55929  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.449  rustc            55931  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.500  rustc            55933  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.571  rustc            55935  55564    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.572  rustc            55936  55513    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.576  rustc            55935  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.576  rustc            55936  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.577  rustc            55953  55549    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.578  execsnoop        55954  55646    0 /usr/local/bin/execsnoop -t\n23.578  python3          55954  55646    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n23.587  docker           55971  55564    0 /usr/bin/docker --help\n23.587  docker           55972  55513    0 /usr/bin/docker --help\n23.599  docker           55991  55513    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.600  rustc            55953  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.600  docker           55992  55564    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.601  rustc            55998  55829    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.607  rustc            55998  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.612  runc             56022  1599     0 /usr/bin/runc --version\n23.612  runc             56023  1599     0 /usr/bin/runc --version\n23.614  rustc            56034  55792    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.615  docker-init      56035  1599     0 /usr/bin/docker-init --version\n23.615  docker-init      56036  1599     0 /usr/bin/docker-init --version\n23.616  docker           56040  55549    0 \n23.616  docker           56039  55564    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.617  docker           56045  55513    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.621  docker           56066  55829    0 /usr/bin/docker --help\n23.621  rustc            56034  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.629  runc             56091  1599     0 /usr/bin/runc --version\n23.629  runc             56092  1599     0 /usr/bin/runc --version\n23.630  docker           56093  55549    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.633  docker           56110  55792    0 /usr/bin/docker --help\n23.633  docker-init      56109  1599     0 /usr/bin/docker-init --version\n23.635  docker           56111  55829    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.636  docker-init      56112  1599     0 /usr/bin/docker-init --version\n23.637  rustc            56120  55684    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.643  rustc            56120  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.646  runc             56144  1599     0 /usr/bin/runc --version\n23.647  runc             56150  1599     0 /usr/bin/runc --version\n23.649  docker           56155  55792    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.649  docker-init      56157  1599     0 /usr/bin/docker-init --version\n23.650  docker           56158  55549    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.650  docker-init      56159  1599     0 /usr/bin/docker-init --version\n23.652  docker           56174  55829    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.656  docker           56183  55684    0 /usr/bin/docker --help\n23.660  rustup           56204  55513    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.661  rustup           56205  55564    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.663  runc             56206  1599     0 /usr/bin/runc --version\n23.663  runc             56207  1599     0 /usr/bin/runc --version\n23.665  runc             56237  1599     0 /usr/bin/runc --version\n23.665  docker-init      56238  1599     0 /usr/bin/docker-init --version\n23.666  docker-init      56244  1599     0 /usr/bin/docker-init --version\n23.667  docker           56245  55792    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.668  rustup           56246  55513    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.668  rustup           56247  55564    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.668  docker-init      56248  1599     0 /usr/bin/docker-init --version\n23.670  docker           56254  55684    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.681  runc             56288  1599     0 /usr/bin/runc --version\n23.683  runc             56294  1599     0 /usr/bin/runc --version\n23.685  docker-init      56300  1599     0 /usr/bin/docker-init --version\n23.686  docker-init      56301  1599     0 /usr/bin/docker-init --version\n23.688  docker           56302  55684    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.693  rustup           56308  55829    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.694  rustup           56309  55513    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.696  rustup           56318  55549    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.699  rustup           56334  55564    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.702  runc             56342  1599     0 /usr/bin/runc --version\n23.704  rustup           56354  55829    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.705  docker-init      56355  1599     0 /usr/bin/docker-init --version\n23.710  rustup           56364  55792    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.716  rustup           56373  55792    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.721  uname            56382  55513    0 /usr/bin/uname -r\n23.727  uname            56383  55564    0 /usr/bin/uname -r\n23.730  rustup           56384  55549    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.732  rustup           56385  55829    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.736  rustup           56402  55684    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.742  rustup           56411  55792    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.742  docker           56413  55513    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.744  rustup           56412  55684    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n"
}
```

#### Record 33

```json
{
  "argv": [
    "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 51592,
  "build_script_target_dir": "libc-c3c858474dcfa7e6",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build",
  "pid": 51592,
  "ppid": 51026,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "_build_script_out_dir": "/target/debug/build/libc-c3c858474dcfa7e6/out"
}
```

#### Record 34

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 51592,
  "build_script_target_dir": "libc-c3c858474dcfa7e6",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 51595,
  "ppid": 51592,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "_build_script_out_dir": "/target/debug/build/libc-c3c858474dcfa7e6/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 35

```json
{
  "argv": [
    "/target/debug/build/ring-36133a68ed4b831a/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/ring-36133a68ed4b831a/build-script-build",
  "pid": 52442,
  "ppid": 51026,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out"
}
```

#### Record 36

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-E",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/6354968475943257539detect_compiler_family.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 52443,
  "ppid": 52442,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 37

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-E",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/6354968475943257539detect_compiler_family.c",
    "-msecure-plt",
    "-mcpu=power8",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 52444,
  "ppid": 52443,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 38

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 52446,
  "ppid": 52442,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 39

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 52447,
  "ppid": 52442,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 40

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/curve25519/curve25519.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "curve25519.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/fad98b632b8ce3cc-curve25519.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 52450,
  "ppid": 52447,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 41

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/fad98b632b8ce3cc-curve25519.o",
    "/tmp/ccsHZLYY.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 52481,
  "ppid": 52447,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 42

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 52486,
  "ppid": 52442,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 43

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/aes/aes_nohw.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "aes_nohw.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca4b6ef5433f5aeb-aes_nohw.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 52488,
  "ppid": 52486,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 44

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca4b6ef5433f5aeb-aes_nohw.o",
    "/tmp/cc4HfcgV.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 52492,
  "ppid": 52486,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 45

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 52493,
  "ppid": 52442,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 46

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/bn/montgomery.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "montgomery.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca8bd8684bb569fa-montgomery.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 52494,
  "ppid": 52493,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 47

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca8bd8684bb569fa-montgomery.o",
    "/tmp/ccve0ris.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 52495,
  "ppid": 52493,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 48

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 52499,
  "ppid": 52442,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 49

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/bn/montgomery_inv.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "montgomery_inv.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca8bd8684bb569fa-montgomery_inv.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 52502,
  "ppid": 52499,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 50

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca8bd8684bb569fa-montgomery_inv.o",
    "/tmp/ccD7T2WV.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 52519,
  "ppid": 52499,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 51

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 52520,
  "ppid": 52442,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 52

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/ecp_nistz.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "ecp_nistz.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-ecp_nistz.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 52521,
  "ppid": 52520,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 53

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-ecp_nistz.o",
    "/tmp/ccdON4Rt.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 52524,
  "ppid": 52520,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 54

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 52525,
  "ppid": 52442,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 55

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/gfp_p256.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "gfp_p256.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-gfp_p256.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 52526,
  "ppid": 52525,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 56

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-gfp_p256.o",
    "/tmp/ccAwWwmT.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 52528,
  "ppid": 52525,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 57

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 52533,
  "ppid": 52442,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 58

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/gfp_p384.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "gfp_p384.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-gfp_p384.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 52536,
  "ppid": 52533,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 59

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-gfp_p384.o",
    "/tmp/ccxeUnMt.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 52543,
  "ppid": 52533,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 60

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 52546,
  "ppid": 52442,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 61

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/p256.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "p256.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-p256.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 52548,
  "ppid": 52546,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 62

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-p256.o",
    "/tmp/cc1LYoCs.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 52555,
  "ppid": 52546,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 63

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 52558,
  "ppid": 52442,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 64

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/limbs/limbs.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "limbs.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a1949f2101df4b9c-limbs.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 52559,
  "ppid": 52558,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 65

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a1949f2101df4b9c-limbs.o",
    "/tmp/cczOmiIp.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 52569,
  "ppid": 52558,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 66

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 52570,
  "ppid": 52442,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 67

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/mem.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "mem.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/7effb53edfc7fa2d-mem.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 52571,
  "ppid": 52570,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 68

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/7effb53edfc7fa2d-mem.o",
    "/tmp/ccSAHVqk.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 52574,
  "ppid": 52570,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 69

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 52575,
  "ppid": 52442,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 70

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/poly1305/poly1305.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "poly1305.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/bec76f70393ddef1-poly1305.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 52577,
  "ppid": 52575,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 71

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/bec76f70393ddef1-poly1305.o",
    "/tmp/ccsim2LG.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 52581,
  "ppid": 52575,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 72

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cq",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/libring_core_0_17_8_.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/fad98b632b8ce3cc-curve25519.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca4b6ef5433f5aeb-aes_nohw.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca8bd8684bb569fa-montgomery.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca8bd8684bb569fa-montgomery_inv.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-ecp_nistz.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-gfp_p256.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-gfp_p384.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-p256.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a1949f2101df4b9c-limbs.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/7effb53edfc7fa2d-mem.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/bec76f70393ddef1-poly1305.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 52582,
  "ppid": 52442,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 73

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "s",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/libring_core_0_17_8_.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 52586,
  "ppid": 52442,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 74

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-E",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/6733488901769689594detect_compiler_family.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 52588,
  "ppid": 52442,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 75

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-E",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/6733488901769689594detect_compiler_family.c",
    "-msecure-plt",
    "-mcpu=power8",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 52589,
  "ppid": 52588,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 76

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 52591,
  "ppid": 52442,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 77

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 52592,
  "ppid": 52442,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 78

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/constant_time_test.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "constant_time_test.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/7effb53edfc7fa2d-constant_time_test.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 52594,
  "ppid": 52592,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 79

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/7effb53edfc7fa2d-constant_time_test.o",
    "/tmp/cc3EP6gZ.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 52615,
  "ppid": 52592,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 80

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cq",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/libring_core_0_17_8_test.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/7effb53edfc7fa2d-constant_time_test.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 52617,
  "ppid": 52442,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 81

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "s",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/libring_core_0_17_8_test.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52442,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 52619,
  "ppid": 52442,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 82

```json
{
  "argv": [
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52625,
  "build_script_target_dir": "rustls-2216ddcaf0bdcdf8",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build-script-build",
  "pid": 52625,
  "ppid": 51026,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "_build_script_out_dir": "/target/debug/build/rustls-2216ddcaf0bdcdf8/out"
}
```

#### Record 83

```json
{
  "crate": "rustls",
  "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "event_id": "bsrun:11df0b4c28e4d2fd:aa8e620880ea118c:01382d2620d23103",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
  "out_dir": "/target/debug/build/rustls-2216ddcaf0bdcdf8/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
  "success": true,
  "target": null,
  "version": "0.21.12",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
    "source": "cwd_prefix"
  }
}
```

#### Record 84

```json
{
  "crate": "libc",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "event_id": "bsrun:2b971722f0fa3d65:9d24ac71553b3fba:82a359e119a38779",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "out_dir": "/target/debug/build/libc-c3c858474dcfa7e6/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
  "success": true,
  "target": null,
  "version": "0.2.153",
  "_owner": {
    "crate": "libc",
    "version": "0.2.153",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
    "source": "cwd_prefix"
  }
}
```

#### Record 85

```json
{
  "crate": "ring",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "event_id": "bsrun:2eaee6c2f99d45ae:4314c542618c32dc:20249890c987169f",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/ring-36133a68ed4b831a/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
  "success": true,
  "target": null,
  "version": "0.17.8",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  }
}
```

#### Record 86

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 51592,
  "build_script_target_dir": "libc-c3c858474dcfa7e6",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 51595,
  "ppid": 51592,
  "root_cargo_pid": 51026,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 87

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/curve25519/curve25519.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "curve25519.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/fad98b632b8ce3cc-curve25519.o",
    "..."
  ],
  "src": "crypto/curve25519/curve25519.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/fad98b632b8ce3cc-curve25519.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52450,
  "ppid": 52447,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51026,
  "build_script_root_pid": 52442,
  "build_script_related": true,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 88

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/aes/aes_nohw.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "aes_nohw.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca4b6ef5433f5aeb-aes_nohw.o",
    "..."
  ],
  "src": "crypto/fipsmodule/aes/aes_nohw.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca4b6ef5433f5aeb-aes_nohw.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52488,
  "ppid": 52486,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51026,
  "build_script_root_pid": 52442,
  "build_script_related": true,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 89

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/bn/montgomery.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "montgomery.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca8bd8684bb569fa-montgomery.o",
    "..."
  ],
  "src": "crypto/fipsmodule/bn/montgomery.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca8bd8684bb569fa-montgomery.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52494,
  "ppid": 52493,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51026,
  "build_script_root_pid": 52442,
  "build_script_related": true,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 90

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/bn/montgomery_inv.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "montgomery_inv.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca8bd8684bb569fa-montgomery_inv.o",
    "..."
  ],
  "src": "crypto/fipsmodule/bn/montgomery_inv.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca8bd8684bb569fa-montgomery_inv.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52502,
  "ppid": 52499,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51026,
  "build_script_root_pid": 52442,
  "build_script_related": true,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 91

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/ecp_nistz.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "ecp_nistz.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-ecp_nistz.o",
    "..."
  ],
  "src": "crypto/fipsmodule/ec/ecp_nistz.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-ecp_nistz.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52521,
  "ppid": 52520,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51026,
  "build_script_root_pid": 52442,
  "build_script_related": true,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 92

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/gfp_p256.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "gfp_p256.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-gfp_p256.o",
    "..."
  ],
  "src": "crypto/fipsmodule/ec/gfp_p256.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-gfp_p256.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52526,
  "ppid": 52525,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51026,
  "build_script_root_pid": 52442,
  "build_script_related": true,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 93

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/gfp_p384.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "gfp_p384.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-gfp_p384.o",
    "..."
  ],
  "src": "crypto/fipsmodule/ec/gfp_p384.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-gfp_p384.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52536,
  "ppid": 52533,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51026,
  "build_script_root_pid": 52442,
  "build_script_related": true,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 94

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/p256.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "p256.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-p256.o",
    "..."
  ],
  "src": "crypto/fipsmodule/ec/p256.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-p256.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52548,
  "ppid": 52546,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51026,
  "build_script_root_pid": 52442,
  "build_script_related": true,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 95

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/limbs/limbs.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "limbs.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a1949f2101df4b9c-limbs.o",
    "..."
  ],
  "src": "crypto/limbs/limbs.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a1949f2101df4b9c-limbs.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52559,
  "ppid": 52558,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51026,
  "build_script_root_pid": 52442,
  "build_script_related": true,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 96

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/mem.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "mem.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/7effb53edfc7fa2d-mem.o",
    "..."
  ],
  "src": "crypto/mem.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/7effb53edfc7fa2d-mem.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52571,
  "ppid": 52570,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51026,
  "build_script_root_pid": 52442,
  "build_script_related": true,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 97

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/poly1305/poly1305.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "poly1305.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/bec76f70393ddef1-poly1305.o",
    "..."
  ],
  "src": "crypto/poly1305/poly1305.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/bec76f70393ddef1-poly1305.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52577,
  "ppid": 52575,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51026,
  "build_script_root_pid": 52442,
  "build_script_related": true,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 98

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/constant_time_test.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "constant_time_test.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/7effb53edfc7fa2d-constant_time_test.o",
    "..."
  ],
  "src": "crypto/constant_time_test.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/7effb53edfc7fa2d-constant_time_test.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52594,
  "ppid": 52592,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51026,
  "build_script_root_pid": 52442,
  "build_script_related": true,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 99

```json
{
  "event": "archive",
  "tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "real_tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cq",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/libring_core_0_17_8_.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/fad98b632b8ce3cc-curve25519.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca4b6ef5433f5aeb-aes_nohw.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca8bd8684bb569fa-montgomery.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca8bd8684bb569fa-montgomery_inv.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-ecp_nistz.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-gfp_p256.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-gfp_p384.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-p256.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a1949f2101df4b9c-limbs.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/7effb53edfc7fa2d-mem.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/bec76f70393ddef1-poly1305.o"
  ],
  "archive": "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/libring_core_0_17_8_.a",
  "objects": [
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/fad98b632b8ce3cc-curve25519.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca4b6ef5433f5aeb-aes_nohw.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca8bd8684bb569fa-montgomery.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca8bd8684bb569fa-montgomery_inv.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-ecp_nistz.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-gfp_p256.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-gfp_p384.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-p256.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a1949f2101df4b9c-limbs.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/7effb53edfc7fa2d-mem.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/bec76f70393ddef1-poly1305.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 52582,
  "ppid": 52442,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51026,
  "build_script_root_pid": 52442,
  "build_script_related": true,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 100

```json
{
  "event": "archive",
  "tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "real_tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cq",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/libring_core_0_17_8_test.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/7effb53edfc7fa2d-constant_time_test.o"
  ],
  "archive": "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/libring_core_0_17_8_test.a",
  "objects": [
    "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/7effb53edfc7fa2d-constant_time_test.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 52617,
  "ppid": 52442,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51026,
  "build_script_root_pid": 52442,
  "build_script_related": true,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "_owner": {
    "crate": "ring",
    "version": "0.17.8",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "_build_script_out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T01:33:27.841315+00:00",
  "crate": "rustls",
  "version": "0.21.12",
  "architecture": "ppc64le",
  "duration_seconds": 32.27324311528355,
  "trace_record_count": 85,
  "trace_owner_summary": {
    "owner_package_count": 37,
    "owner_packages": [
      {
        "crate": "wasi",
        "version": "0.11.0+wasi-snapshot-preview1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.11.0+wasi-snapshot-preview1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.0+wasi-snapshot-preview1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.0+wasi-snapshot-preview1/Cargo.toml"
      },
      {
        "crate": "windows_aarch64_gnullvm",
        "version": "0.52.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.52.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.5/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_gnullvm",
        "version": "0.52.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.52.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.5/Cargo.toml"
      },
      {
        "crate": "windows_aarch64_msvc",
        "version": "0.52.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.52.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.5/Cargo.toml"
      },
      {
        "crate": "windows_i686_gnullvm",
        "version": "0.52.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnullvm@0.52.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnullvm-0.52.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnullvm-0.52.5/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.5/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_gnu",
        "version": "0.52.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.52.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.5/Cargo.toml"
      },
      {
        "crate": "windows_i686_msvc",
        "version": "0.52.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.52.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.5/Cargo.toml"
      },
      {
        "crate": "windows_i686_gnu",
        "version": "0.52.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.52.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.5/Cargo.toml"
      },
      {
        "crate": "windows-targets",
        "version": "0.52.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.52.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.5/Cargo.toml"
      },
      {
        "crate": "rustls-webpki",
        "version": "0.101.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustls-webpki@0.101.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustls-webpki-0.101.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustls-webpki-0.101.7/Cargo.toml"
      },
      {
        "crate": "regex-automata",
        "version": "0.4.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.6/Cargo.toml"
      },
      {
        "crate": "rustls-pemfile",
        "version": "1.0.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustls-pemfile@1.0.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustls-pemfile-1.0.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustls-pemfile-1.0.4/Cargo.toml"
      },
      {
        "crate": "webpki-roots",
        "version": "0.25.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#webpki-roots@0.25.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/webpki-roots-0.25.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/webpki-roots-0.25.4/Cargo.toml"
      },
      {
        "crate": "aho-corasick",
        "version": "1.1.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.3/Cargo.toml"
      },
      {
        "crate": "is-terminal",
        "version": "0.4.12",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#is-terminal@0.4.12",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/is-terminal-0.4.12",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/is-terminal-0.4.12/Cargo.toml"
      },
      {
        "crate": "regex-syntax",
        "version": "0.8.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.3/Cargo.toml"
      },
      {
        "crate": "windows-sys",
        "version": "0.52.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.52.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.52.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.52.0/Cargo.toml"
      },
      {
        "crate": "env_logger",
        "version": "0.10.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#env_logger@0.10.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/env_logger-0.10.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/env_logger-0.10.2/Cargo.toml"
      },
      {
        "crate": "winapi-util",
        "version": "0.1.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.8",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.8/Cargo.toml"
      },
      {
        "crate": "getrandom",
        "version": "0.2.14",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.2.14",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.14",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.14/Cargo.toml"
      },
      {
        "crate": "hermit-abi",
        "version": "0.3.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#hermit-abi@0.3.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.3.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.3.9/Cargo.toml"
      },
      {
        "crate": "humantime",
        "version": "2.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#humantime@2.1.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/humantime-2.1.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/humantime-2.1.0/Cargo.toml"
      },
      {
        "crate": "termcolor",
        "version": "1.4.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#termcolor@1.4.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.1/Cargo.toml"
      },
      {
        "crate": "untrusted",
        "version": "0.9.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#untrusted@0.9.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/untrusted-0.9.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/untrusted-0.9.0/Cargo.toml"
      },
      {
        "crate": "base64",
        "version": "0.21.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#base64@0.21.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/base64-0.21.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/base64-0.21.7/Cargo.toml"
      },
      {
        "crate": "bencher",
        "version": "0.1.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bencher@0.1.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bencher-0.1.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bencher-0.1.5/Cargo.toml"
      },
      {
        "crate": "cfg-if",
        "version": "1.0.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "2.7.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.2/Cargo.toml"
      },
      {
        "crate": "regex",
        "version": "1.10.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.10.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.10.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.10.4/Cargo.toml"
      },
      {
        "crate": "ring",
        "version": "0.17.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/Cargo.toml"
      },
      {
        "crate": "log",
        "version": "0.4.21",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.21",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.21",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.21/Cargo.toml"
      },
      {
        "crate": "spin",
        "version": "0.9.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#spin@0.9.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/spin-0.9.8",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/spin-0.9.8/Cargo.toml"
      },
      {
        "crate": "cc",
        "version": "1.0.95",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.95",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.95",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.95/Cargo.toml"
      },
      {
        "crate": "sct",
        "version": "0.7.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#sct@0.7.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/sct-0.7.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/sct-0.7.1/Cargo.toml"
      },
      {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
        "manifest_path": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12/Cargo.toml"
      }
    ],
    "attributed_event_count": 33,
    "unattributed_event_count": 52,
    "owners": [
      {
        "crate": "rustls",
        "version": "0.21.12",
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
      },
      {
        "crate": "libc",
        "version": "0.2.153",
        "event_count": 10,
        "kind_counts": {
          "exec": 1,
          "used_input": 5,
          "link": 1,
          "exec_context": 1,
          "resolved_link": 1,
          "build_script_run": 1
        }
      },
      {
        "crate": "ring",
        "version": "0.17.8",
        "event_count": 10,
        "kind_counts": {
          "exec": 1,
          "used_input": 5,
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
      "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "workspace_root": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.3",
          "name": "aho-corasick",
          "version": "1.1.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#base64@0.21.7",
          "name": "base64",
          "version": "0.21.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/base64-0.21.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/base64-0.21.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bencher@0.1.5",
          "name": "bencher",
          "version": "0.1.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bencher-0.1.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bencher-0.1.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.95",
          "name": "cc",
          "version": "1.0.95",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.95/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.95"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
          "name": "cfg-if",
          "version": "1.0.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#env_logger@0.10.2",
          "name": "env_logger",
          "version": "0.10.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/env_logger-0.10.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/env_logger-0.10.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.2.14",
          "name": "getrandom",
          "version": "0.2.14",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.14/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.14"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#hermit-abi@0.3.9",
          "name": "hermit-abi",
          "version": "0.3.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.3.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.3.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#humantime@2.1.0",
          "name": "humantime",
          "version": "2.1.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/humantime-2.1.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/humantime-2.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#is-terminal@0.4.12",
          "name": "is-terminal",
          "version": "0.4.12",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/is-terminal-0.4.12/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/is-terminal-0.4.12"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
          "name": "libc",
          "version": "0.2.153",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.21",
          "name": "log",
          "version": "0.4.21",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.21/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.21"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.2",
          "name": "memchr",
          "version": "2.7.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.10.4",
          "name": "regex",
          "version": "1.10.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.10.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.10.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.6",
          "name": "regex-automata",
          "version": "0.4.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.3",
          "name": "regex-syntax",
          "version": "0.8.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
          "name": "ring",
          "version": "0.17.8",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8"
        },
        {
          "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
          "name": "rustls",
          "version": "0.21.12",
          "manifest_path": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustls-pemfile@1.0.4",
          "name": "rustls-pemfile",
          "version": "1.0.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustls-pemfile-1.0.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustls-pemfile-1.0.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustls-webpki@0.101.7",
          "name": "rustls-webpki",
          "version": "0.101.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustls-webpki-0.101.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustls-webpki-0.101.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#sct@0.7.1",
          "name": "sct",
          "version": "0.7.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/sct-0.7.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/sct-0.7.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#spin@0.9.8",
          "name": "spin",
          "version": "0.9.8",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/spin-0.9.8/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/spin-0.9.8"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#termcolor@1.4.1",
          "name": "termcolor",
          "version": "1.4.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#untrusted@0.9.0",
          "name": "untrusted",
          "version": "0.9.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/untrusted-0.9.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/untrusted-0.9.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.11.0+wasi-snapshot-preview1",
          "name": "wasi",
          "version": "0.11.0+wasi-snapshot-preview1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.0+wasi-snapshot-preview1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.0+wasi-snapshot-preview1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#webpki-roots@0.25.4",
          "name": "webpki-roots",
          "version": "0.25.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/webpki-roots-0.25.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/webpki-roots-0.25.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.8",
          "name": "winapi-util",
          "version": "0.1.8",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.8/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.8"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.52.0",
          "name": "windows-sys",
          "version": "0.52.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.52.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.52.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.52.5",
          "name": "windows-targets",
          "version": "0.52.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.52.5",
          "name": "windows_aarch64_gnullvm",
          "version": "0.52.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.52.5",
          "name": "windows_aarch64_msvc",
          "version": "0.52.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.52.5",
          "name": "windows_i686_gnu",
          "version": "0.52.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnullvm@0.52.5",
          "name": "windows_i686_gnullvm",
          "version": "0.52.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnullvm-0.52.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnullvm-0.52.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.52.5",
          "name": "windows_i686_msvc",
          "version": "0.52.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.52.5",
          "name": "windows_x86_64_gnu",
          "version": "0.52.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.52.5",
          "name": "windows_x86_64_gnullvm",
          "version": "0.52.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.5",
          "name": "windows_x86_64_msvc",
          "version": "0.52.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.5"
        }
      ],
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "exit_code": 0,
      "kind": "exec",
      "pid": 51188,
      "ppid": 51110,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rustls",
      "cargo_pkg_version": "0.21.12",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "event_id": "used:cc:7b3816f9d77727d6:3cc7127cb83a9aa0:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
      "pid": 51188,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rustls",
      "cargo_pkg_version": "0.21.12",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "event_id": "used:cc:7b3816f9d77727d6:24aaf905568abeeb:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
      "pid": 51188,
      "sha256": "b9857273de0f0eb6790f4bcddeb10e4bdf58d7884145fa18844ac18b87b010a0",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rustls",
      "cargo_pkg_version": "0.21.12",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "event_id": "used:cc:7b3816f9d77727d6:1659140dd49f7bf6:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
      "pid": 51188,
      "sha256": "b93ad444dcce8804c7b36e41be48e297f3f75aec602915da266de464042a864a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rustls",
      "cargo_pkg_version": "0.21.12",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "event_id": "used:cc:7b3816f9d77727d6:403fdecfd9e88adb:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
      "pid": 51188,
      "sha256": "e16192e82a6a55409bb0ddeef9ecb826a2a1e726b5d774e19517a36fdc2c80e3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rustls",
      "cargo_pkg_version": "0.21.12",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "event_id": "used:cc:7b3816f9d77727d6:0f40e438d5159b12:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
      "pid": 51188,
      "sha256": "a322b0c5d63af985eb903640674e12de9b6a791f9ddeae6e96a64138b759f000",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rustls",
      "cargo_pkg_version": "0.21.12",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "event_id": "used:cc:7b3816f9d77727d6:79ee593c0724e8a2:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
      "pid": 51188,
      "sha256": "466bf857385651585270a3062a18deff4adad60e1d93c4cf765ef7f15822c7a9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rustls",
      "cargo_pkg_version": "0.21.12",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "event_id": "used:cc:7b3816f9d77727d6:9c44d4c80b5dfb72:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
      "pid": 51188,
      "sha256": "2a6cf24c0a0269e4833fdfcff9cd095c0e58be7a7e310e83ace955edb2ba5340",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
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
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "cargo_pkg_name": "rustls",
      "cargo_pkg_version": "0.21.12",
      "context_path": "/tmp/native-trace-50171-1783992780090/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-50171-1783992780090/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 51188,
      "ppid": 51110,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8",
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
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcnA7SNw/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.15gvzq8.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.15gvzq8.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.15gvzq8.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.15gvzq8.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.15gvzq8.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.15gvzq8.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-51188-1783992783891210956.map",
      "pid": 51188,
      "ppid": 51110,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-51188-1783992783891210956.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "exit_code": 0,
      "kind": "exec",
      "pid": 51463,
      "ppid": 51102,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.153",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "event_id": "used:cc:b47364ada97c6bc2:d2e7d9c14f456d4c:6abd7aadaee76ef4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
      "pid": 51463,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.153",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "event_id": "used:cc:b47364ada97c6bc2:8fbc204c2de40ae3:6abd7aadaee76ef4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
      "pid": 51463,
      "sha256": "1c1bda37289ec1d821d844082238c8264f2503ddb9285e4c4b35874be718b5b0",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.153",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "event_id": "used:cc:b47364ada97c6bc2:8fa1e6b2f28555cd:6abd7aadaee76ef4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
      "pid": 51463,
      "sha256": "5e70191dfb043a5385388b604c5c1feba8fec2b44fdb25873028a427923b8d6a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.153",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "event_id": "used:cc:b47364ada97c6bc2:56ea4f27c87e1fc7:6abd7aadaee76ef4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
      "pid": 51463,
      "sha256": "8197d6a77e8ee592aad69945794d29560ea22f5d99de7fd4a19d8a5ec3c53dd4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.153",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "event_id": "used:cc:b47364ada97c6bc2:6ef887c52156788c:6abd7aadaee76ef4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
      "pid": 51463,
      "sha256": "9f762bbe468a79bebb41c2e60a430efa1e822b7c5745db8269c41350de4cf6f5",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/raw-dylibs",
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
      "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.153",
      "context_path": "/tmp/native-trace-50171-1783992780090/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-50171-1783992780090/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 51463,
      "ppid": 51102,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "_owner": {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4",
        "/target/debug/build/libc-c3c858474dcfa7e6",
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
          "directory": "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4",
          "kind": "object",
          "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustc6mXOq4/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-c3c858474dcfa7e6",
          "kind": "object",
          "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-c3c858474dcfa7e6",
          "kind": "object",
          "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-c3c858474dcfa7e6",
          "kind": "object",
          "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-c3c858474dcfa7e6",
          "kind": "object",
          "path": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-51463-1783992784204685603.map",
      "pid": 51463,
      "ppid": 51102,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-51463-1783992784204685603.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
      "exit_code": 0,
      "kind": "exec",
      "pid": 52402,
      "ppid": 52351,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ring",
        "version": "0.17.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ring",
      "cargo_pkg_version": "0.17.8",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
      "event_id": "used:cc:d3ed579287892b7b:79161489f646a2f5:0983853cb5c6903e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
      "path": "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
      "pid": 52402,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ring",
        "version": "0.17.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ring",
      "cargo_pkg_version": "0.17.8",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
      "event_id": "used:cc:d3ed579287892b7b:bf7722017c206f9e:0983853cb5c6903e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
      "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
      "pid": 52402,
      "sha256": "025527fb46fcb2d3fc121ee840b5e1003a1d506b6ad7cda5c827f0415c6617e3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ring",
        "version": "0.17.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ring",
      "cargo_pkg_version": "0.17.8",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
      "event_id": "used:cc:d3ed579287892b7b:29db5b508b5dac78:0983853cb5c6903e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
      "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
      "pid": 52402,
      "sha256": "b8d0e2f4da86f4e5439d83c7aedf252d0395627a3a4070292812a2e95453eab1",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ring",
        "version": "0.17.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ring",
      "cargo_pkg_version": "0.17.8",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
      "event_id": "used:cc:d3ed579287892b7b:750b69807bdb0049:0983853cb5c6903e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
      "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
      "pid": 52402,
      "sha256": "1473c60f65c2830cec9ad1acc6f763ed7f8bbed33d8426cb25651a2190e4f471",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ring",
        "version": "0.17.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "ring",
      "cargo_pkg_version": "0.17.8",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
      "event_id": "used:cc:d3ed579287892b7b:349090cbd640d504:0983853cb5c6903e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
      "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
      "pid": 52402,
      "sha256": "ef84c5450bab83b8ef3f7972151a3ee714a0a4b83e5707bb18cab99aff3090fb",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ring",
        "version": "0.17.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/raw-dylibs",
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
      "output": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "ring",
        "version": "0.17.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
      "cargo_pkg_name": "ring",
      "cargo_pkg_version": "0.17.8",
      "context_path": "/tmp/native-trace-50171-1783992780090/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-50171-1783992780090/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 52402,
      "ppid": 52351,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "_owner": {
        "crate": "ring",
        "version": "0.17.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV",
        "/target/debug/build/ring-36133a68ed4b831a",
        "/target/debug/deps",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "/lib/x86_64-linux-gnu",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55740            55740        c    16         /target/debug/build/ring-36133a68ed4b831a",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55750            55750        c    16         /target/debug/build/ring-36133a68ed4b831a",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/598d0            598d0        c    16         /target/debug/build/ring-36133a68ed4b831a",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/637b0            637b0        9    16         /target/debug/build/ring-36133a68ed4b831a",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/637c0            637c0        9    16         /target/debug/build/ring-36133a68ed4b831a"
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
          "directory": "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV",
          "kind": "object",
          "path": "/target/debug/build/ring-36133a68ed4b831a/rustciwvlQV/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ring-36133a68ed4b831a",
          "kind": "object",
          "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ring-36133a68ed4b831a",
          "kind": "object",
          "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ring-36133a68ed4b831a",
          "kind": "object",
          "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/ring-36133a68ed4b831a",
          "kind": "object",
          "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.00.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.02.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.03.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.04.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.05.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.01.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.06.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.07.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.08.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.09.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.10.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.11.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.12.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.13.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.14.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7c98ac3bfc277f7f.rlib(cc-7c98ac3bfc277f7f.cc.f93c23fc5b4408a7-cgu.15.rcgu.o",
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
        },
        {
          "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55740            55740        c    16         /target/debug/build/ring-36133a68ed4b831a",
          "kind": "dynamic_library",
          "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55740            55740        c    16         /target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN102_$LT$core..iter..adapters..filter..Filter$LT$I$C$P$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h366b1fdc5249421eE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/build/ring-36133a68ed4b831a",
          "kind": "dynamic_library",
          "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN102_$LT$core..iter..adapters..filter..Filter$LT$I$C$P$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h366b1fdc5249421eE",
          "source": "link_map"
        },
        {
          "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55750            55750        c    16         /target/debug/build/ring-36133a68ed4b831a",
          "kind": "dynamic_library",
          "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55750            55750        c    16         /target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN102_$LT$core..iter..adapters..filter..Filter$LT$I$C$P$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17hdd043471a900c196E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/build/ring-36133a68ed4b831a",
          "kind": "dynamic_library",
          "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN102_$LT$core..iter..adapters..filter..Filter$LT$I$C$P$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17hdd043471a900c196E",
          "source": "link_map"
        },
        {
          "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/598d0            598d0        c    16         /target/debug/build/ring-36133a68ed4b831a",
          "kind": "dynamic_library",
          "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/598d0            598d0        c    16         /target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h522cca2806a5a384E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/build/ring-36133a68ed4b831a",
          "kind": "dynamic_library",
          "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h522cca2806a5a384E",
          "source": "link_map"
        },
        {
          "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/637b0            637b0        9    16         /target/debug/build/ring-36133a68ed4b831a",
          "kind": "dynamic_library",
          "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/637b0            637b0        9    16         /target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o:(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h3c3f8f1374e45b16E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/build/ring-36133a68ed4b831a",
          "kind": "dynamic_library",
          "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o:(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h3c3f8f1374e45b16E",
          "source": "link_map"
        },
        {
          "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/637c0            637c0        9    16         /target/debug/build/ring-36133a68ed4b831a",
          "kind": "dynamic_library",
          "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/637c0            637c0        9    16         /target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o:(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h5f762ba4a5828b0bE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/build/ring-36133a68ed4b831a",
          "kind": "dynamic_library",
          "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o:(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h5f762ba4a5828b0bE",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "/tmp/native-trace-link-cc-52402-1783992785697521466.map",
      "pid": 52402,
      "ppid": 52351,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-52402-1783992785697521466.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "ring",
        "version": "0.17.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
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
      "parsed_event_count": 894,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 895,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": " 1 --filter-platform aarch64-unknown-linux-gnu\n17.725  runc             54622  49060    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892b --log-format json --systemd-cgroup kill --all 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a 9\n17.734  runc             54628  49060    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892b --log-format json --systemd-cgroup delete 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a\n17.739  cargo            54606  54542    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n17.750  runc             54634  54537    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc031 --log-format json --systemd-cgroup start 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0\n17.754  rustc            54640  54606    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.757  sh               54570  54537    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.758  cargo            54641  54570    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.767  rustc            54643  54606    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.772  cargo-native-tr  54641  54570    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.777  cargo            54645  54641    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.782  rustc            54648  54606    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.792  rustc            54651  54645    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.804  rustc            54654  54645    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.822  rustc            54658  54542    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.845  rustc            54658  54542    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.856  docker           54670  54542    0 /usr/bin/docker --help\n17.861  execsnoop        54676  54641    0 /usr/local/bin/execsnoop -t\n17.861  python3          54676  54641    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.869  docker           54687  54542    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.880  runc             54696  46492    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f49 --log-format json --systemd-cgroup kill --all a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922 9\n17.880  runc             54697  1599     0 /usr/bin/runc --version\n17.883  docker-init      54708  1599     0 /usr/bin/docker-init --version\n17.884  docker           54709  54542    0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.887  runc             54715  46492    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f49 --log-format json --systemd-cgroup delete a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922\n17.896  runc             54726  1599     0 /usr/bin/runc --version\n17.899  docker-init      54732  1599     0 /usr/bin/docker-init --version\n17.919  rustup           54733  54542    0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.933  containerd-shim  54743  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892b delete\n17.935  runc             54750  54743    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9 --log-format json delete --force 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a\n17.942  rustup           54755  54542    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.966  rustup           54764  54542    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.966  systemd-sysctl   54765  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe425dec --prefix=/net/ipv4/neigh/vethe425dec --prefix=/net/ipv6/conf/vethe425dec --prefix=/net/ipv6/neigh/vethe425dec\n17.990  uname            54774  54542    0 /usr/bin/uname -r\n18.007  docker           54775  54542    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n18.044  systemd-sysctl   54789  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth76e10a3 --prefix=/net/ipv4/neigh/veth76e10a3 --prefix=/net/ipv6/conf/veth76e10a3 --prefix=/net/ipv6/neigh/veth76e10a3\n18.044  systemd-sysctl   54788  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf2069ec --prefix=/net/ipv4/neigh/vethf2069ec --prefix=/net/ipv6/conf/vethf2069ec --prefix=/net/ipv6/neigh/vethf2069ec\n18.059  containerd-shim  54791  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 start\n18.062  containerd-shim  54798  54791    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 -address /var/run/docker/containerd/containerd.sock\n18.066  runc             54808  54798    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10\n18.067  containerd-shim  54811  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f49 delete\n18.069  runc             54820  54811    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f495792 --log-format json delete --force a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922\n18.071  exe              54827  54808    0 /proc/self/exe init\n18.106  systemd-sysctl   54832  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7f2e47d --prefix=/net/ipv4/neigh/veth7f2e47d --prefix=/net/ipv6/conf/veth7f2e47d --prefix=/net/ipv6/neigh/veth7f2e47d\n18.121  exe              54838  54808    0 /proc/1599/exe -exec-root=/var/run/docker 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 d7da31e8f8e1\n18.140  exe              54846  1599     0 /proc/self/exe /var/run/docker/netns/3e401da5d4b2 all false\n18.200  runc             54864  54798    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --log-format json --systemd-cgroup start 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10\n18.205  sh               54831  54798    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n18.206  cargo            54870  54831    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n18.217  cargo-native-tr  54870  54831    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n18.220  cargo            54871  54870    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n18.230  rustc            54872  54871    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.242  rustc            54874  54871    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n18.251  runc             54878  49386    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b --log-format json --systemd-cgroup kill --all bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888 9\n18.268  runc             54885  49386    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b --log-format json --systemd-cgroup delete bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888\n18.280  execsnoop        54891  54870    0 /usr/local/bin/execsnoop -t\n18.280  python3          54891  54870    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n18.294  runc             54894  49353    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 --log-format json --systemd-cgroup kill --all a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7 9\n18.312  runc             54901  49353    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 --log-format json --systemd-cgroup delete a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7\n18.489  containerd-shim  54907  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b delete\n18.491  runc             54914  54907    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf788 --log-format json delete --force bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888\n18.528  systemd-sysctl   54919  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethfb8276c --prefix=/net/ipv4/neigh/vethfb8276c --prefix=/net/ipv6/conf/vethfb8276c --prefix=/net/ipv6/neigh/vethfb8276c\n18.536  containerd-shim  54921  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 delete\n18.538  runc             54928  54921    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f --log-format json delete --force a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7\n18.581  systemd-sysctl   54933  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth651aca6 --prefix=/net/ipv4/neigh/veth651aca6 --prefix=/net/ipv6/conf/veth651aca6 --prefix=/net/ipv6/neigh/veth651aca6\n18.648  runc             54934  49256    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 --log-format json --systemd-cgroup kill --all f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96 9\n18.664  runc             54940  49256    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 --log-format json --systemd-cgroup delete f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96\n18.845  containerd-shim  54946  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 delete\n18.848  runc             54953  54946    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da9 --log-format json delete --force f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96\n18.885  systemd-sysctl   54959  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd600a16 --prefix=/net/ipv4/neigh/vethd600a16 --prefix=/net/ipv6/conf/vethd600a16 --prefix=/net/ipv6/neigh/vethd600a16\n18.953  runc             54961  49929    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d --log-format json --systemd-cgroup kill --all 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637 9\n18.960  runc             54967  49929    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d --log-format json --systemd-cgroup delete 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637\n19.139  containerd-shim  54974  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d delete\n19.142  runc             54981  54974    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d9863 --log-format json delete --force 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637\n19.177  systemd-sysctl   54986  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5b8f709 --prefix=/net/ipv4/neigh/veth5b8f709 --prefix=/net/ipv6/conf/veth5b8f709 --prefix=/net/ipv6/neigh/veth5b8f709\n19.288  sh               54987  2147557   0 /bin/sh -c which ps\n19.289  which            54987  2147557   0 /usr/bin/which ps\n19.291  sh               54988  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n19.292  ps               54988  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n19.317  sh               54989  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n19.318  cpuUsage.sh      54989  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n19.319  sed              54990  54989    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n19.321  cat              54991  54989    0 /usr/bin/cat /proc/2240539/stat\n19.322  cat              54992  54989    0 /usr/bin/cat /proc/4193716/stat\n19.323  sleep            54993  54989    0 /usr/bin/sleep 1\n19.716  cargo            54994  54641    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n19.729  rustc            54995  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n19.758  rustc            55001  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n19.798  cc               55024  55001    0 /tmp/native-trace-54641-1783992801298/shims/cc -m64 /target/debug/build/valuable-0ca3a52e87f47781/rustcum31Fu/symbols.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2bcuvqydoknozqmp1me20ruil.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2hvolwvrh1z7h0esed9fdlkq6.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2ydqatcbwpyv0nfser2rvjw0s.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.320kk89i2c31bqlrt1pe5ftwu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.3dorb0xb6tyxiuzsrh06fg7wn.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.44p8ua3isbvp2so96dfqsrcv0.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.4mgnn3dy9r06fb4dhef909zhp.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54olwytbg728sxv8s6jzea9ac.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54xlj1thl6ekctt4ryak72mpk.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5gyye0zaqcjlw0qa72458hp4p.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5m686vmv93io6lluiiyhiylju.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.7d19io80brmbzee20rw5urjmi.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.b7inlg8jykc014dunu01jjkqu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.c3a0y0h3kjig5bmjwukot6pmm.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.deexadt1dri1ihovsh8z1lp29.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.dlbacscotl41na11230m8gkv8.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.e0jqet5ubfmmb5vnbm2c21wdk.15hdgiv.rcgu.o ...\n19.799  cc               55025  55024    0 /usr/bin/cc -m64 /target/debug/build/valuable-0ca3a52e87f47781/rustcum31Fu/symbols.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2bcuvqydoknozqmp1me20ruil.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2hvolwvrh1z7h0esed9fdlkq6.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2ydqatcbwpyv0nfser2rvjw0s.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.320kk89i2c31bqlrt1pe5ftwu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.3dorb0xb6tyxiuzsrh06fg7wn.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.44p8ua3isbvp2so96dfqsrcv0.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.4mgnn3dy9r06fb4dhef909zhp.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54olwytbg728sxv8s6jzea9ac.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54xlj1thl6ekctt4ryak72mpk.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5gyye0zaqcjlw0qa72458hp4p.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5m686vmv93io6lluiiyhiylju.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.7d19io80brmbzee20rw5urjmi.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.b7inlg8jykc014dunu01jjkqu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.c3a0y0h3kjig5bmjwukot6pmm.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.deexadt1dri1ihovsh8z1lp29.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.dlbacscotl41na11230m8gkv8.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.e0jqet5ubfmmb5vnbm2c21wdk.15hdgiv.rcgu.o ...\n19.802  collect2         55026  55025    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.803  ld.lld           55027  55026    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781 ...\n19.804  rust-lld         55027  55026    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.842  build-script-bu  55045  54994    0 /target/debug/build/valuable-0ca3a52e87f47781/build-script-build\n19.846  rustc            55047  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name valuable --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n20.126  cargo            55059  54870    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n20.138  rustc            55070  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.164  rustc            55113  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n20.164  rustc            55111  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.18/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=ba1b82e103e0280b ...\n20.263  cc               55188  55113    0 /tmp/native-trace-54870-1783992801742/shims/cc -m64 /target/debug/build/proc-macro2-46239aad0aaf2dde/rustcz8FJmv/symbols.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0bv3et31ep2k9sd4r4xv6yltt.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0edhhq7oafgl2yf0nrxumcg9r.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0g0902jm3uya6wioho7beok0j.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0owef7ksnbk6ukcc2242nefkr.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0rdzizyhqamtksvgo7enpq5az.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1r69zij4wcxunk2gd17a0kpg6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1sghvgwc08k4idxie37yo3pw0.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1wbfjtyvleo9dhvql6dw9ezks.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2om80ctxk1ydfs1240ujhhg0b.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2ylb2sbb9n609gy1nl3eivm1m.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.34jg2bcz8z6kfpvajxful9pig.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3dgkawms7tf7icnefiv8uh2ur.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3h5kxyomdhio13fti327b3ul4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3pfht32bkan9uc6xs96laffv6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3vy5vc4kvl4zobt41ffusuic4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3wfb4bv7o9ei3djc1ma3hgool.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.4sen9su2ywavj025286hzh4rs.0uq14k2.rcgu.o ...\n20.264  cc               55189  55188    0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-46239aad0aaf2dde/rustcz8FJmv/symbols.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0bv3et31ep2k9sd4r4xv6yltt.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0edhhq7oafgl2yf0nrxumcg9r.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0g0902jm3uya6wioho7beok0j.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0owef7ksnbk6ukcc2242nefkr.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0rdzizyhqamtksvgo7enpq5az.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1r69zij4wcxunk2gd17a0kpg6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1sghvgwc08k4idxie37yo3pw0.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1wbfjtyvleo9dhvql6dw9ezks.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2om80ctxk1ydfs1240ujhhg0b.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2ylb2sbb9n609gy1nl3eivm1m.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.34jg2bcz8z6kfpvajxful9pig.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3dgkawms7tf7icnefiv8uh2ur.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3h5kxyomdhio13fti327b3ul4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3pfht32bkan9uc6xs96laffv6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3vy5vc4kvl4zobt41ffusuic4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3wfb4bv7o9ei3djc1ma3hgool.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.4sen9su2ywavj025286hzh4rs.0uq14k2.rcgu.o ...\n20.267  collect2         55190  55189    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n20.269  ld.lld           55191  55190    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde ...\n20.270  rust-lld         55191  55190    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n20.325  sed              55209  54989    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n20.325  build-script-bu  55210  55059    0 /target/debug/build/proc-macro2-46239aad0aaf2dde/build-script-build\n20.326  cat              55211  54989    0 /usr/bin/cat /proc/2240539/stat\n20.327  rustc            55212  55210    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n20.328  cat              55214  54989    0 /usr/bin/cat /proc/4193716/stat\n20.337  rustc            55217  55210    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-1a2ad12dc9160ce7/out/probe build/probe.rs --target aarch64-unknown-linux-gnu\n20.364  rustc            55222  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n20.929  cross            55331  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.930  rustc            55334  55331    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.951  rustc            55334  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.963  rustc            55346  55331    0 /home/xmoe/.cargo/bin/rustc -vV\n20.984  rustc            55346  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.994  cargo            55356  55331    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.015  cargo            55356  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.026  rustc            55366  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.028  git              55365  2235138   0 /usr/bin/git config --get commit.template\n21.035  rustc            55368  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.043  git              55369  2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n21.046  rustc            55373  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.059  git              55374  2235138   0 /usr/bin/git status -z -uall\n21.071  rustc            55379  55331    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n21.074  git              55378  2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n21.093  rustc            55379  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n21.104  docker           55391  55331    0 /usr/bin/docker --help\n21.116  docker           55402  55331    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n21.128  runc             55412  1599     0 /usr/bin/runc --version\n21.131  docker-init      55418  1599     0 /usr/bin/docker-init --version\n21.132  docker           55419  55331    0 /usr/bin/docker info -f {{.SecurityOptions}}\n21.142  runc             55430  1599     0 /usr/bin/runc --version\n21.146  docker-init      55436  1599     0 /usr/bin/docker-init --version\n21.166  rustup           55440  55331    0 /home/xmoe/.cargo/bin/rustup toolchain list\n21.188  rustup           55449  55331    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n21.209  rustup           55458  55331    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n21.233  uname            55467  55331    0 /usr/bin/uname -r\n21.248  docker           55468  55331    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n21.284  systemd-sysctl   55483  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8170368 --prefix=/net/ipv4/neigh/veth8170368 --prefix=/net/ipv6/conf/veth8170368 --prefix=/net/ipv6/neigh/veth8170368\n21.284  systemd-sysctl   55482  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth81dd9a9 --prefix=/net/ipv4/neigh/veth81dd9a9 --prefix=/net/ipv6/conf/veth81dd9a9 --prefix=/net/ipv6/neigh/veth81dd9a9\n21.297  containerd-shim  55484  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 start\n21.300  containerd-shim  55491  55484    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 -address /var/run/docker/containerd/containerd.sock\n21.304  runc             55501  55491    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956\n21.309  exe              55509  55501    0 /proc/self/exe init\n21.327  cross            55513  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n21.328  rustc            55520  55513    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.333  rustc            55520  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.342  exe              55532  55501    0 /proc/1599/exe -exec-root=/var/run/docker 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 d7da31e8f8e1\n21.344  rustc            55539  55513    0 /home/xmoe/.cargo/bin/rustc -vV\n21.349  rustc            55539  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.355  cross            55549  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n21.356  rustc            55552  55549    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.359  cargo            55561  55513    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n21.359  cross            55564  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n21.361  rustc            55567  55564    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.362  exe              55576  1599     0 /proc/self/exe /var/run/docker/netns/8b628a44607d all false\n21.364  cargo            55561  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n21.365  rustc            55567  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.374  rustc            55596  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.377  rustc            55597  55564    0 /home/xmoe/.cargo/bin/rustc -vV\n21.382  rustc            55552  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.383  rustc            55597  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.384  rustc            55607  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.391  cargo            55614  55564    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.393  rustc            55616  55549    0 /home/xmoe/.cargo/bin/rustc -vV\n21.394  rustc            55625  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.396  cargo            55614  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.407  rustc            55637  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.409  runc             55639  55491    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --log-format json --systemd-cgroup start 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956\n21.414  sh               55511  55491    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n21.415  cargo            55646  55511    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n21.416  rustc            55647  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.419  rustc            55616  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.427  cargo-native-tr  55646  55511    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n21.428  cargo            55652  55549    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n21.429  rustc            55653  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.431  cargo            55654  55646    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n21.441  rustc            55666  55654    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.450  cargo            55652  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n21.453  rustc            55668  55654    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.460  rustc            55670  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.469  rustc            55674  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.482  rustc            55678  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.518  git              55683  2235138   0 /usr/bin/git worktree list --porcelain\n21.556  cross            55684  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n21.557  rustc            55687  55684    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.561  rustc            55687  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.573  runc             55701  47737    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a --log-format json --systemd-cgroup kill --all 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9 9\n21.573  rustc            55700  55684    0 /home/xmoe/.cargo/bin/rustc -vV\n21.578  rustc            55700  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.587  cargo            55716  55684    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.590  runc             55725  47737    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a --log-format json --systemd-cgroup delete 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9\n21.591  cargo            55716  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.601  rustc            55731  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.611  rustc            55733  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.634  rustc            55737  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.719  runc             55741  49799    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e --log-format json --systemd-cgroup kill --all f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e 9\n21.726  runc             55748  49799    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e --log-format json --systemd-cgroup delete f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e\n21.806  containerd-shim  55754  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a delete\n21.808  runc             55761  55754    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a --log-format json delete --force 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9\n21.811  runc             55767  50023    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc --log-format json --systemd-cgroup kill --all a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0 9\n21.827  runc             55773  50023    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc --log-format json --systemd-cgroup delete a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0\n21.850  systemd-sysctl   55779  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethae76c09 --prefix=/net/ipv4/neigh/vethae76c09 --prefix=/net/ipv6/conf/vethae76c09 --prefix=/net/ipv6/neigh/vethae76c09\n21.913  runc             55780  50289    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d67 --log-format json --systemd-cgroup kill --all 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb 9\n21.930  runc             55786  50289    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d67 --log-format json --systemd-cgroup delete 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb\n21.961  cross            55792  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n21.963  rustc            55795  55792    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.968  rustc            55795  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.979  rustc            55807  55792    0 /home/xmoe/.cargo/bin/rustc -vV\n21.984  rustc            55807  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.986  containerd-shim  55816  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e delete\n21.989  runc             55822  55816    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1 --log-format json delete --force f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e\n21.991  cross            55829  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n21.992  rustc            55832  55829    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.993  cargo            55833  55792    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.997  rustc            55832  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.997  cargo            55833  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n22.007  rustc            55853  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.009  rustc            55854  55829    0 /home/xmoe/.cargo/bin/rustc -vV\n22.014  rustc            55854  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.016  rustc            55864  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n22.023  cargo            55869  55829    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n22.025  systemd-sysctl   55870  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethddd6c57 --prefix=/net/ipv4/neigh/vethddd6c57 --prefix=/net/ipv6/conf/vethddd6c57 --prefix=/net/ipv6/neigh/vethddd6c57\n22.026  containerd-shim  55880  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc delete\n22.028  rustc            55884  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n22.028  cargo            55869  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n22.029  runc             55887  55880    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f --log-format json delete --force a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0\n22.038  rustc            55896  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.047  rustc            55898  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n22.059  rustc            55902  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n22.066  systemd-sysctl   55903  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf192d49 --prefix=/net/ipv4/neigh/vethf192d49 --prefix=/net/ipv6/conf/vethf192d49 --prefix=/net/ipv6/neigh/vethf192d49\n22.154  containerd-shim  55908  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d67 delete\n22.156  runc             55915  55908    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7c --log-format json delete --force 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb\n22.187  systemd-sysctl   55920  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7b4cddd --prefix=/net/ipv4/neigh/veth7b4cddd --prefix=/net/ipv6/conf/veth7b4cddd --prefix=/net/ipv6/neigh/veth7b4cddd\n23.325  rustc            55925  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.374  rustc            55927  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.401  rustc            55929  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.449  rustc            55931  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.500  rustc            55933  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.571  rustc            55935  55564    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.572  rustc            55936  55513    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.576  rustc            55935  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.576  rustc            55936  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.577  rustc            55953  55549    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.578  execsnoop        55954  55646    0 /usr/local/bin/execsnoop -t\n23.578  python3          55954  55646    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n23.587  docker           55971  55564    0 /usr/bin/docker --help\n23.587  docker           55972  55513    0 /usr/bin/docker --help\n23.599  docker           55991  55513    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.600  rustc            55953  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.600  docker           55992  55564    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.601  rustc            55998  55829    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.607  rustc            55998  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.612  runc             56022  1599     0 /usr/bin/runc --version\n23.612  runc             56023  1599     0 /usr/bin/runc --version\n23.614  rustc            56034  55792    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.615  docker-init      56035  1599     0 /usr/bin/docker-init --version\n23.615  docker-init      56036  1599     0 /usr/bin/docker-init --version\n23.616  docker           56040  55549    0 \n23.616  docker           56039  55564    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.617  docker           56045  55513    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.621  docker           56066  55829    0 /usr/bin/docker --help\n23.621  rustc            56034  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.629  runc             56091  1599     0 /usr/bin/runc --version\n23.629  runc             56092  1599     0 /usr/bin/runc --version\n23.630  docker           56093  55549    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.633  docker           56110  55792    0 /usr/bin/docker --help\n23.633  docker-init      56109  1599     0 /usr/bin/docker-init --version\n23.635  docker           56111  55829    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.636  docker-init      56112  1599     0 /usr/bin/docker-init --version\n23.637  rustc            56120  55684    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.643  rustc            56120  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.646  runc             56144  1599     0 /usr/bin/runc --version\n23.647  runc             56150  1599     0 /usr/bin/runc --version\n23.649  docker           56155  55792    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.649  docker-init      56157  1599     0 /usr/bin/docker-init --version\n23.650  docker           56158  55549    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.650  docker-init      56159  1599     0 /usr/bin/docker-init --version\n23.652  docker           56174  55829    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.656  docker           56183  55684    0 /usr/bin/docker --help\n23.660  rustup           56204  55513    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.661  rustup           56205  55564    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.663  runc             56206  1599     0 /usr/bin/runc --version\n23.663  runc             56207  1599     0 /usr/bin/runc --version\n23.665  runc             56237  1599     0 /usr/bin/runc --version\n23.665  docker-init      56238  1599     0 /usr/bin/docker-init --version\n23.666  docker-init      56244  1599     0 /usr/bin/docker-init --version\n23.667  docker           56245  55792    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.668  rustup           56246  55513    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.668  rustup           56247  55564    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.668  docker-init      56248  1599     0 /usr/bin/docker-init --version\n23.670  docker           56254  55684    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.681  runc             56288  1599     0 /usr/bin/runc --version\n23.683  runc             56294  1599     0 /usr/bin/runc --version\n23.685  docker-init      56300  1599     0 /usr/bin/docker-init --version\n23.686  docker-init      56301  1599     0 /usr/bin/docker-init --version\n23.688  docker           56302  55684    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.693  rustup           56308  55829    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.694  rustup           56309  55513    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.696  rustup           56318  55549    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.699  rustup           56334  55564    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.702  runc             56342  1599     0 /usr/bin/runc --version\n23.704  rustup           56354  55829    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.705  docker-init      56355  1599     0 /usr/bin/docker-init --version\n23.710  rustup           56364  55792    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.716  rustup           56373  55792    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.721  uname            56382  55513    0 /usr/bin/uname -r\n23.727  uname            56383  55564    0 /usr/bin/uname -r\n23.730  rustup           56384  55549    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.732  rustup           56385  55829    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.736  rustup           56402  55684    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.742  rustup           56411  55792    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.742  docker           56413  55513    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.744  rustup           56412  55684    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n"
    },
    {
      "argv": [
        "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 51592,
      "build_script_target_dir": "libc-c3c858474dcfa7e6",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build",
      "pid": 51592,
      "ppid": 51026,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 51592,
      "build_script_target_dir": "libc-c3c858474dcfa7e6",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 51595,
      "ppid": 51592,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/ring-36133a68ed4b831a/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/ring-36133a68ed4b831a/build-script-build",
      "pid": 52442,
      "ppid": 51026,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-E",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/6354968475943257539detect_compiler_family.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 52443,
      "ppid": 52442,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-E",
        "-quiet",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/6354968475943257539detect_compiler_family.c",
        "-msecure-plt",
        "-mcpu=power8",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 52444,
      "ppid": 52443,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 52446,
      "ppid": 52442,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 52447,
      "ppid": 52442,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/curve25519/curve25519.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "curve25519.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/fad98b632b8ce3cc-curve25519.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 52450,
      "ppid": 52447,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/fad98b632b8ce3cc-curve25519.o",
        "/tmp/ccsHZLYY.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 52481,
      "ppid": 52447,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 52486,
      "ppid": 52442,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/aes/aes_nohw.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "aes_nohw.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca4b6ef5433f5aeb-aes_nohw.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 52488,
      "ppid": 52486,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca4b6ef5433f5aeb-aes_nohw.o",
        "/tmp/cc4HfcgV.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 52492,
      "ppid": 52486,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 52493,
      "ppid": 52442,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/bn/montgomery.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "montgomery.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca8bd8684bb569fa-montgomery.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 52494,
      "ppid": 52493,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca8bd8684bb569fa-montgomery.o",
        "/tmp/ccve0ris.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 52495,
      "ppid": 52493,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 52499,
      "ppid": 52442,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/bn/montgomery_inv.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "montgomery_inv.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca8bd8684bb569fa-montgomery_inv.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 52502,
      "ppid": 52499,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca8bd8684bb569fa-montgomery_inv.o",
        "/tmp/ccD7T2WV.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 52519,
      "ppid": 52499,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 52520,
      "ppid": 52442,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/ec/ecp_nistz.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "ecp_nistz.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-ecp_nistz.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 52521,
      "ppid": 52520,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-ecp_nistz.o",
        "/tmp/ccdON4Rt.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 52524,
      "ppid": 52520,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 52525,
      "ppid": 52442,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/ec/gfp_p256.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "gfp_p256.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-gfp_p256.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 52526,
      "ppid": 52525,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-gfp_p256.o",
        "/tmp/ccAwWwmT.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 52528,
      "ppid": 52525,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 52533,
      "ppid": 52442,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/ec/gfp_p384.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "gfp_p384.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-gfp_p384.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 52536,
      "ppid": 52533,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-gfp_p384.o",
        "/tmp/ccxeUnMt.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 52543,
      "ppid": 52533,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 52546,
      "ppid": 52442,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/ec/p256.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "p256.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-p256.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 52548,
      "ppid": 52546,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-p256.o",
        "/tmp/cc1LYoCs.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 52555,
      "ppid": 52546,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 52558,
      "ppid": 52442,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/limbs/limbs.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "limbs.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a1949f2101df4b9c-limbs.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 52559,
      "ppid": 52558,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a1949f2101df4b9c-limbs.o",
        "/tmp/cczOmiIp.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 52569,
      "ppid": 52558,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 52570,
      "ppid": 52442,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/mem.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "mem.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/7effb53edfc7fa2d-mem.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 52571,
      "ppid": 52570,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/7effb53edfc7fa2d-mem.o",
        "/tmp/ccSAHVqk.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 52574,
      "ppid": 52570,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 52575,
      "ppid": 52442,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/poly1305/poly1305.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "poly1305.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/bec76f70393ddef1-poly1305.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 52577,
      "ppid": 52575,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/bec76f70393ddef1-poly1305.o",
        "/tmp/ccsim2LG.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 52581,
      "ppid": 52575,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "cq",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/libring_core_0_17_8_.a",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/fad98b632b8ce3cc-curve25519.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca4b6ef5433f5aeb-aes_nohw.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca8bd8684bb569fa-montgomery.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/ca8bd8684bb569fa-montgomery_inv.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-ecp_nistz.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-gfp_p256.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-gfp_p384.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a9af75d892b04b75-p256.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/a1949f2101df4b9c-limbs.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/7effb53edfc7fa2d-mem.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/bec76f70393ddef1-poly1305.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 52582,
      "ppid": 52442,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "s",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/libring_core_0_17_8_.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 52586,
      "ppid": 52442,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-E",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/6733488901769689594detect_compiler_family.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 52588,
      "ppid": 52442,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-E",
        "-quiet",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/6733488901769689594detect_compiler_family.c",
        "-msecure-plt",
        "-mcpu=power8",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 52589,
      "ppid": 52588,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 52591,
      "ppid": 52442,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 52592,
      "ppid": 52442,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/constant_time_test.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "constant_time_test.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/7effb53edfc7fa2d-constant_time_test.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 52594,
      "ppid": 52592,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/7effb53edfc7fa2d-constant_time_test.o",
        "/tmp/cc3EP6gZ.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 52615,
      "ppid": 52592,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "cq",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/libring_core_0_17_8_test.a",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/7effb53edfc7fa2d-constant_time_test.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 52617,
      "ppid": 52442,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "s",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/ring-d3dbdf76a2c2527d/out/libring_core_0_17_8_test.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52442,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 52619,
      "ppid": 52442,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52625,
      "build_script_target_dir": "rustls-2216ddcaf0bdcdf8",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build-script-build",
      "pid": 52625,
      "ppid": 51026,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "rustls",
      "cwd": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "event_id": "bsrun:11df0b4c28e4d2fd:aa8e620880ea118c:01382d2620d23103",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
      "out_dir": "/target/debug/build/rustls-2216ddcaf0bdcdf8/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
      "success": true,
      "target": null,
      "version": "0.21.12",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-ppc64le-jc851iyo/src/rustls-0.21.12",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "libc",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "event_id": "bsrun:2b971722f0fa3d65:9d24ac71553b3fba:82a359e119a38779",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "out_dir": "/target/debug/build/libc-c3c858474dcfa7e6/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
      "success": true,
      "target": null,
      "version": "0.2.153",
      "_owner": {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "ring",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
      "event_id": "bsrun:2eaee6c2f99d45ae:4314c542618c32dc:20249890c987169f",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/ring-36133a68ed4b831a/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
      "out_dir": "/target/debug/build/ring-36133a68ed4b831a/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
      "success": true,
      "target": null,
      "version": "0.17.8",
      "_owner": {
        "crate": "ring",
        "version": "0.17.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ring@0.17.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 51592,
      "build_script_target_dir": "libc-c3c858474dcfa7e6",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 51595,
      "ppid": 51592,
      "root_cargo_pid": 51026,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 302,
    "crate": "rustls",
    "version": "0.21.12",
    "crate_id": "6137",
    "version_id": "1127217",
    "downloads": 100929469,
    "cumulative_downloads": 55367817584,
    "cumulative_share_of_global": 0.20700748796391344,
    "status": "ok",
    "has_build_script": true,
    "build_script_path": "build.rs",
    "build_script_exists": true,
    "package_build_field": "build.rs",
    "build_script_reason": "package_build_path",
    "download_source": "local"
  }
}
```
