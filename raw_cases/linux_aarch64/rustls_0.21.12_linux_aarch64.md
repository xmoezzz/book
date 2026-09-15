# `rustls` `0.21.12`

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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM",
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
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-51913-1783992784680408562.map",
  "pid": 51913,
  "ppid": 51832,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-51913-1783992784680408562.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
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
  "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "workspace_root": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12"
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
      "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
      "name": "rustls",
      "version": "0.21.12",
      "manifest_path": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12"
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
    "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "exit_code": 0,
  "kind": "exec",
  "pid": 51913,
  "ppid": 51832,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "event_id": "used:cc:c42419fcc1bb316a:fab8fe6a994f4e05:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
  "pid": 51913,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "event_id": "used:cc:c42419fcc1bb316a:9c396efe95e3798a:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
  "pid": 51913,
  "sha256": "c6eaa5a3126fd4f5af824fad2289d1dba511352408a2c76327fffa9a2bbf1118",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "event_id": "used:cc:c42419fcc1bb316a:81133837f6ebb247:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
  "pid": 51913,
  "sha256": "9532727822144c0567ab989f643960e118eeef51d0b03f45a33a5d24fde31d49",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "event_id": "used:cc:c42419fcc1bb316a:8ecaed9234a82d15:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
  "pid": 51913,
  "sha256": "c926f0d80b9db98309ea373d7d925d16448fdd102cdaa73601edda00562f8a30",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "event_id": "used:cc:c42419fcc1bb316a:2c99fba7eefc3c38:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
  "pid": 51913,
  "sha256": "7f033c8e48115010e778ebb040c38069ea3eccabb0d9630fec159b11bde2b2f8",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "event_id": "used:cc:c42419fcc1bb316a:6b7214eb8cbc327c:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
  "pid": 51913,
  "sha256": "9d068557d15915decb6945225220ee80a4167b5a2ff586bad30f9d19f74a97c4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "event_id": "used:cc:c42419fcc1bb316a:4193d58c6908a17d:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
  "pid": 51913,
  "sha256": "2a6cf24c0a0269e4833fdfcff9cd095c0e58be7a7e310e83ace955edb2ba5340",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "cargo_pkg_name": "rustls",
  "cargo_pkg_version": "0.21.12",
  "context_path": "/tmp/native-trace-50494-1783992780436/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-50494-1783992780436/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 51913,
  "ppid": 51832,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM",
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
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-51913-1783992784680408562.map",
  "pid": 51913,
  "ppid": 51832,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-51913-1783992784680408562.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/raw-dylibs",
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
  "pid": 52137,
  "ppid": 51818,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/raw-dylibs",
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
  "event_id": "used:cc:b47364ada97c6bc2:c6dea2fad6a37f38:6abd7aadaee76ef4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
  "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
  "pid": 52137,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/raw-dylibs",
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
  "pid": 52137,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/raw-dylibs",
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
  "pid": 52137,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/raw-dylibs",
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
  "pid": 52137,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/raw-dylibs",
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
  "pid": 52137,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/raw-dylibs",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/raw-dylibs",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/raw-dylibs",
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
  "context_path": "/tmp/native-trace-50494-1783992780436/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-50494-1783992780436/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 52137,
  "ppid": 51818,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/raw-dylibs",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk",
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
      "directory": "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk",
      "kind": "object",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
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
  "map_path": "/tmp/native-trace-link-cc-52137-1783992785012666856.map",
  "pid": 52137,
  "ppid": 51818,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-52137-1783992785012666856.map"
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/raw-dylibs",
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
  "pid": 52496,
  "ppid": 52455,
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/raw-dylibs",
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
  "event_id": "used:cc:d3ed579287892b7b:23a293744c001c76:0983853cb5c6903e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
  "path": "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
  "pid": 52496,
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/raw-dylibs",
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
  "pid": 52496,
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/raw-dylibs",
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
  "pid": 52496,
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/raw-dylibs",
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
  "pid": 52496,
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/raw-dylibs",
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
  "pid": 52496,
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/raw-dylibs",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/raw-dylibs",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/raw-dylibs",
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
  "context_path": "/tmp/native-trace-50494-1783992780436/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-50494-1783992780436/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 52496,
  "ppid": 52455,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/raw-dylibs",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG",
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
      "directory": "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG",
      "kind": "object",
      "path": "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
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
  "map_path": "/tmp/native-trace-link-cc-52496-1783992786109873056.map",
  "pid": 52496,
  "ppid": 52455,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-52496-1783992786109873056.map"
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
  "parse_error_count": 2,
  "parsed_event_count": 940,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 942,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "47  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name valuable --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n19.381  cargo            55059  54870    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n19.394  rustc            55070  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n19.419  rustc            55113  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n19.420  rustc            55111  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.18/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=ba1b82e103e0280b ...\n19.518  cc               55188  55113    0 /tmp/native-trace-54870-1783992801742/shims/cc -m64 /target/debug/build/proc-macro2-46239aad0aaf2dde/rustcz8FJmv/symbols.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0bv3et31ep2k9sd4r4xv6yltt.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0edhhq7oafgl2yf0nrxumcg9r.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0g0902jm3uya6wioho7beok0j.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0owef7ksnbk6ukcc2242nefkr.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0rdzizyhqamtksvgo7enpq5az.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1r69zij4wcxunk2gd17a0kpg6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1sghvgwc08k4idxie37yo3pw0.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1wbfjtyvleo9dhvql6dw9ezks.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2om80ctxk1ydfs1240ujhhg0b.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2ylb2sbb9n609gy1nl3eivm1m.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.34jg2bcz8z6kfpvajxful9pig.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3dgkawms7tf7icnefiv8uh2ur.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3h5kxyomdhio13fti327b3ul4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3pfht32bkan9uc6xs96laffv6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3vy5vc4kvl4zobt41ffusuic4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3wfb4bv7o9ei3djc1ma3hgool.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.4sen9su2ywavj025286hzh4rs.0uq14k2.rcgu.o ...\n19.519  cc               55189  55188    0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-46239aad0aaf2dde/rustcz8FJmv/symbols.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0bv3et31ep2k9sd4r4xv6yltt.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0edhhq7oafgl2yf0nrxumcg9r.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0g0902jm3uya6wioho7beok0j.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0owef7ksnbk6ukcc2242nefkr.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0rdzizyhqamtksvgo7enpq5az.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1r69zij4wcxunk2gd17a0kpg6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1sghvgwc08k4idxie37yo3pw0.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1wbfjtyvleo9dhvql6dw9ezks.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2om80ctxk1ydfs1240ujhhg0b.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2ylb2sbb9n609gy1nl3eivm1m.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.34jg2bcz8z6kfpvajxful9pig.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3dgkawms7tf7icnefiv8uh2ur.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3h5kxyomdhio13fti327b3ul4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3pfht32bkan9uc6xs96laffv6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3vy5vc4kvl4zobt41ffusuic4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3wfb4bv7o9ei3djc1ma3hgool.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.4sen9su2ywavj025286hzh4rs.0uq14k2.rcgu.o ...\n19.523  collect2         55190  55189    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.524  ld.lld           55191  55190    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde ...\n19.526  rust-lld         55191  55190    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.580  sed              55209  54989    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n19.580  build-script-bu  55210  55059    0 /target/debug/build/proc-macro2-46239aad0aaf2dde/build-script-build\n19.582  cat              55211  54989    0 /usr/bin/cat /proc/2240539/stat\n19.582  rustc            55212  55210    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n19.583  cat              55214  54989    0 /usr/bin/cat /proc/4193716/stat\n19.592  rustc            55217  55210    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-1a2ad12dc9160ce7/out/probe build/probe.rs --target aarch64-unknown-linux-gnu\n19.619  rustc            55222  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n20.184  cross            55331  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.185  rustc            55334  55331    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.206  rustc            55334  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.218  rustc            55346  55331    0 /home/xmoe/.cargo/bin/rustc -vV\n20.240  rustc            55346  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.250  cargo            55356  55331    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.271  cargo            55356  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.281  rustc            55366  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.283  git              55365  2235138   0 /usr/bin/git config --get commit.template\n20.290  rustc            55368  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.298  git              55369  2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n20.301  rustc            55373  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.314  git              55374  2235138   0 /usr/bin/git status -z -uall\n20.326  rustc            55379  55331    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n20.330  git              55378  2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n20.348  rustc            55379  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n20.360  docker           55391  55331    0 /usr/bin/docker --help\n20.371  docker           55402  55331    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n20.383  runc             55412  1599     0 /usr/bin/runc --version\n20.386  docker-init      55418  1599     0 /usr/bin/docker-init --version\n20.387  docker           55419  55331    0 /usr/bin/docker info -f {{.SecurityOptions}}\n20.398  runc             55430  1599     0 /usr/bin/runc --version\n20.401  docker-init      55436  1599     0 /usr/bin/docker-init --version\n20.422  rustup           55440  55331    0 /home/xmoe/.cargo/bin/rustup toolchain list\n20.443  rustup           55449  55331    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n20.464  rustup           55458  55331    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n20.488  uname            55467  55331    0 /usr/bin/uname -r\n20.503  docker           55468  55331    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n20.540  systemd-sysctl   55483  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8170368 --prefix=/net/ipv4/neigh/veth8170368 --prefix=/net/ipv6/conf/veth8170368 --prefix=/net/ipv6/neigh/veth8170368\n20.540  systemd-sysctl   55482  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth81dd9a9 --prefix=/net/ipv4/neigh/veth81dd9a9 --prefix=/net/ipv6/conf/veth81dd9a9 --prefix=/net/ipv6/neigh/veth81dd9a9\n20.553  containerd-shim  55484  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 start\n20.556  containerd-shim  55491  1        0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 -address /var/run/docker/containerd/containerd.sock\n20.560  runc             55501  55491    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956\n20.565  exe              55509  55501    0 /proc/self/exe init\n20.583  cross            55513  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n20.584  rustc            55520  55513    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.589  rustc            55520  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.598  exe              55532  55501    0 /proc/1599/exe -exec-root=/var/run/docker 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 d7da31e8f8e1\n20.600  rustc            55539  55513    0 /home/xmoe/.cargo/bin/rustc -vV\n20.605  rustc            55539  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.610  cross            55549  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n20.612  rustc            55552  55549    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.614  cargo            55561  55513    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.615  cross            55564  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.616  rustc            55567  55564    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.618  exe              55576  1599     0 /proc/self/exe /var/run/docker/netns/8b628a44607d all false\n20.620  cargo            55561  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.621  rustc            55567  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.630  rustc            55596  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.633  rustc            55597  55564    0 /home/xmoe/.cargo/bin/rustc -vV\n20.637  rustc            55552  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.638  rustc            55597  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.639  rustc            55607  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.646  cargo            55614  55564    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.649  rustc            55616  55549    0 /home/xmoe/.cargo/bin/rustc -vV\n20.650  rustc            55625  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.652  cargo            55614  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.662  rustc            55637  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.664  runc             55639  55491    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --log-format json --systemd-cgroup start 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956\n20.669  sh               55511  55491    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n20.670  cargo            55646  55511    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n20.672  rustc            55647  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.675  rustc            55616  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.683  cargo-native-tr  55646  55511    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n20.683  cargo            55652  55549    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.684  rustc            55653  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.686  cargo            55654  55646    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n20.696  rustc            55666  55654    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.705  cargo            55652  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.708  rustc            55668  55654    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.716  rustc            55670  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.725  rustc            55674  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.737  rustc            55678  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.773  git              55683  2235138   0 /usr/bin/git worktree list --porcelain\n20.811  cross            55684  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n20.812  rustc            55687  55684    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.817  rustc            55687  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.828  runc             55701  47737    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a --log-format json --systemd-cgroup kill --all 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9 9\n20.828  rustc            55700  55684    0 /home/xmoe/.cargo/bin/rustc -vV\n20.833  rustc            55700  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.842  cargo            55716  55684    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n20.845  runc             55725  47737    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a --log-format json --systemd-cgroup delete 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9\n20.847  cargo            55716  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n20.857  rustc            55731  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.866  rustc            55733  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.889  rustc            55737  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.974  runc             55741  49799    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e --log-format json --systemd-cgroup kill --all f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e 9\n20.982  runc             55748  49799    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e --log-format json --systemd-cgroup delete f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e\n21.061  containerd-shim  55754  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a delete\n21.064  runc             55761  55754    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a --log-format json delete --force 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9\n21.067  runc             55767  50023    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc --log-format json --systemd-cgroup kill --all a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0 9\n21.083  runc             55773  50023    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc --log-format json --systemd-cgroup delete a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0\n21.105  systemd-sysctl   55779  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethae76c09 --prefix=/net/ipv4/neigh/vethae76c09 --prefix=/net/ipv6/conf/vethae76c09 --prefix=/net/ipv6/neigh/vethae76c09\n21.168  runc             55780  50289    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d67 --log-format json --systemd-cgroup kill --all 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb 9\n21.185  runc             55786  50289    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d67 --log-format json --systemd-cgroup delete 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb\n21.217  cross            55792  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n21.218  rustc            55795  55792    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.223  rustc            55795  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.234  rustc            55807  55792    0 /home/xmoe/.cargo/bin/rustc -vV\n21.239  rustc            55807  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.242  containerd-shim  55816  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e delete\n21.244  runc             55822  55816    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1 --log-format json delete --force f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e\n21.247  cross            55829  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n21.248  rustc            55832  55829    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.248  cargo            55833  55792    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.252  rustc            55832  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.252  cargo            55833  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.263  rustc            55853  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.264  rustc            55854  55829    0 /home/xmoe/.cargo/bin/rustc -vV\n21.269  rustc            55854  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.271  rustc            55864  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.278  cargo            55869  55829    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.280  systemd-sysctl   55870  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethddd6c57 --prefix=/net/ipv4/neigh/vethddd6c57 --prefix=/net/ipv6/conf/vethddd6c57 --prefix=/net/ipv6/neigh/vethddd6c57\n21.282  containerd-shim  55880  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc delete\n21.283  rustc            55884  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.284  cargo            55869  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.284  runc             55887  55880    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f --log-format json delete --force a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0\n21.293  rustc            55896  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.303  rustc            55898  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.314  rustc            55902  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.322  systemd-sysctl   55903  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf192d49 --prefix=/net/ipv4/neigh/vethf192d49 --prefix=/net/ipv6/conf/vethf192d49 --prefix=/net/ipv6/neigh/vethf192d49\n21.409  containerd-shim  55908  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d67 delete\n21.411  runc             55915  55908    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7c --log-format json delete --force 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb\n21.443  systemd-sysctl   55920  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7b4cddd --prefix=/net/ipv4/neigh/veth7b4cddd --prefix=/net/ipv6/conf/veth7b4cddd --prefix=/net/ipv6/neigh/veth7b4cddd\n22.580  rustc            55925  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.629  rustc            55927  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.657  rustc            55929  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.704  rustc            55931  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.755  rustc            55933  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.826  rustc            55935  55564    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n22.827  rustc            55936  55513    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n22.831  rustc            55935  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n22.832  rustc            55936  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n22.832  rustc            55953  55549    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n22.833  execsnoop        55954  55646    0 /usr/local/bin/execsnoop -t\n22.834  python3          55954  55646    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n22.842  docker           55971  55564    0 /usr/bin/docker --help\n22.843  docker           55972  55513    0 /usr/bin/docker --help\n22.855  docker           55991  55513    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n22.855  rustc            55953  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n22.856  docker           55992  55564    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n22.857  rustc            55998  55829    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n22.862  rustc            55998  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n22.867  runc             56022  1599     0 /usr/bin/runc --version\n22.868  runc             56023  1599     0 /usr/bin/runc --version\n22.869  rustc            56034  55792    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n22.870  docker-init      56035  1599     0 /usr/bin/docker-init --version\n22.870  docker-init      56036  1599     0 /usr/bin/docker-init --version\n22.871  docker           56039  55564    0 /usr/bin/docker info -f {{.SecurityOptions}}\n22.871  docker           56040  55549    0 /usr/bin/docker --help\n22.872  docker           56045  55513    0 /usr/bin/docker info -f {{.SecurityOptions}}\n22.876  docker           56066  55829    0 /usr/bin/docker --help\n22.876  rustc            56034  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n22.885  runc             56091  1599     0 /usr/bin/runc --version\n22.885  runc             56092  1599     0 /usr/bin/runc --version\n22.885  docker           56093  55549    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n22.888  docker           56110  55792    0 /usr/bin/docker --help\n22.888  docker-init      56109  1599     0 /usr/bin/docker-init --version\n22.891  docker           56111  55829    0 \n22.892  docker-init      56112  1599     0 /usr/bin/docker-init --version\n22.892  rustc            56120  55684    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n22.898  rustc            56120  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n22.901  runc             56144  1599     0 /usr/bin/runc --version\n22.903  runc             56150  1599     0 /usr/bin/runc --version\n22.904  docker           56155  55792    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n22.904  docker-init      56157  1599     0 /usr/bin/docker-init --version\n22.905  docker           56158  55549    0 /usr/bin/docker info -f {{.SecurityOptions}}\n22.906  docker-init      56159  1599     0 /usr/bin/docker-init --version\n22.907  docker           56174  55829    0 /usr/bin/docker info -f {{.SecurityOptions}}\n22.911  docker           56183  55684    0 /usr/bin/docker --help\n22.916  rustup           56204  55513    0 /home/xmoe/.cargo/bin/rustup toolchain list\n22.917  rustup           56205  55564    0 /home/xmoe/.cargo/bin/rustup toolchain list\n22.918  runc             56206  1599     0 /usr/bin/runc --version\n22.918  runc             56207  1599     0 /usr/bin/runc --version\n22.920  runc             56237  1599     0 /usr/bin/runc --version\n22.921  docker-init      56238  1599     0 /usr/bin/docker-init --version\n22.922  docker-init      56244  1599     0 /usr/bin/docker-init --version\n22.922  docker           56245  55792    0 /usr/bin/docker info -f {{.SecurityOptions}}\n22.923  rustup           56246  55513    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n22.923  rustup           56247  55564    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n22.924  docker-init      56248  1599     0 /usr/bin/docker-init --version\n22.926  docker           56254  55684    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n22.936  runc             56288  1599     0 /usr/bin/runc --version\n22.939  runc             56294  1599     0 /usr/bin/runc --version\n22.940  docker-init      56300  1599     0 /usr/bin/docker-init --version\n22.942  docker-init      56301  1599     0 /usr/bin/docker-init --version\n22.944  docker           56302  55684    0 /usr/bin/docker info -f {{.SecurityOptions}}\n22.948  rustup           56308  55829    0 /home/xmoe/.cargo/bin/rustup toolchain list\n22.949  rustup           56309  55513    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n22.952  rustup           56318  55549    0 /home/xmoe/.cargo/bin/rustup toolchain list\n22.955  rustup           56334  55564    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n22.957  runc             56342  1599     0 /usr/bin/runc --version\n22.960  rustup           56354  55829    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n22.960  docker-init      56355  1599     0 /usr/bin/docker-init --version\n22.965  rustup           56364  55792    0 /home/xmoe/.cargo/bin/rustup toolchain list\n22.971  rustup           56373  55792    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n22.977  uname            56382  55513    0 /usr/bin/uname -r\n22.982  uname            56383  55564    0 /usr/bin/uname -r\n22.985  rustup           56384  55549    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n22.987  rustup           56385  55829    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n22.991  rustup           56402  55684    0 /home/xmoe/.cargo/bin/rustup toolchain list\n22.997  rustup           56411  55792    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n22.998  docker           56413  55513    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n22.999  rustup           56412  55684    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.001  docker           56427  55564    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.012  rustup           56452  55549    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.016  uname            56461  55829    0 /usr/bin/uname -r\n23.025  runc             56462  49987    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b --log-format json --systemd-cgroup kill --all 8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b31584 9\n23.026  uname            56463  55792    0 /usr/bin/uname -r\n23.027  rustup           56469  55684    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.034  runc             56478  49987    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b --log-format json --systemd-cgroup delete 8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b31584\n23.041  docker           56484  55829    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.043  uname            56490  55549    0 /usr/bin/uname -r\n23.047  systemd-sysctl   56491  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb7e39a3 --prefix=/net/ipv4/neigh/vethb7e39a3 --prefix=/net/ipv6/conf/vethb7e39a3 --prefix=/net/ipv6/neigh/vethb7e39a3\n23.047  systemd-sysctl   56492  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth22901f8 --prefix=/net/ipv4/neigh/veth22901f8 --prefix=/net/ipv6/conf/veth22901f8 --prefix=/net/ipv6/neigh/veth22901f8\n23.049  docker           56494  55792    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.051  systemd-sysctl   56497  54510    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth17a9353 --prefix=/net/ipv4/neigh/veth17a9353 --prefix=/net/ipv6/conf/veth17a9353 --prefix=/net/ipv6/neigh/veth17a9353\n23.052  systemd-sysctl   56496  54522    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth48cca07 --prefix=/net/ipv4/neigh/veth48cca07 --prefix=/net/ipv6/conf/veth48cca07 --prefix=/net/ipv6/neigh/veth48cca07\n23.060  uname            56504  55684    0 /usr/bin/uname -r\n23.067  docker           56507  55549    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.068  containerd-shim  56508  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a978af6b start\n23.073  containerd-shim  56520  56508    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a978af6b -address /var/run/docker/containerd/containerd.sock\n23.077  runc             56530  56520    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a97 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a97 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a97 42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a978af6b\n23.083  exe              56541  56530    0 /proc/self/exe init\n23.084  docker           56543  55684    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.117  exe              56568  56530    0 /proc/1599/exe -exec-root=/var/run/docker 42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a978af6b d7da31e8f8e1\n23.137  exe              56576  1599     0 /proc/self/exe /var/run/docker/netns/952f96b918e5 all false\n23.162  runc             56589  48833    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/68355959d765aad8bf227fa53691f1da7c78466af4739606e5535912ada --log-format json --systemd-cgroup kill --all 68355959d765aad8bf227fa53691f1da7c78466af4739606e5535912ada85424 9\n23.168  runc             56596  48833    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/68355959d765aad8bf227fa53691f1da7c78466af4739606e5535912ada --log-format json --systemd-cgroup delete 68355959d765aad8bf227fa53691f1da7c78466af4739606e5535912ada85424\n23.169  containerd-shim  56599  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id fa2299019308ccdc0d053e4b83f0a87826a0d2c4c83ed0216afa2eb3c8314462 start\n23.171  systemd-sysctl   56606  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf8a38fd --prefix=/net/ipv4/neigh/vethf8a38fd --prefix=/net/ipv6/conf/vethf8a38fd --prefix=/net/ipv6/neigh/vethf8a38fd\n23.171  systemd-sysctl   56607  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth6fc7c7e --prefix=/net/ipv4/neigh/veth6fc7c7e --prefix=/net/ipv6/conf/veth6fc7c7e --prefix=/net/ipv6/neigh/veth6fc7c7e\n23.172  containerd-shim  56610  56599    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id fa2299019308ccdc0d053e4b83f0a87826a0d2c4c83ed0216afa2eb3c8314462 -address /var/run/docker/containerd/containerd.sock\n23.175  runc             56620  56610    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fa2299019308ccdc0d053e4b83f0a87826a0d2c4c83ed0216afa2eb3c83 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fa2299019308ccdc0d053e4b83f0a87826a0d2c4c83ed0216afa2eb3c83 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fa2299019308ccdc0d053e4b83f0a87826a0d2c4c83ed0216afa2eb3c83 fa2299019308ccdc0d053e4b83f0a87826a0d2c4c83ed0216afa2eb3c8314462\n23.178  runc             56626  56520    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a97 --log-format json --systemd-cgroup start 42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a978af6b\n23.183  exe              56635  56620    0 /proc/self/exe init\n23.185  sh               56561  56520    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n23.185  cargo            56636  56561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n23.196  cargo-native-tr  56636  56561    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n23.199  cargo            56637  56636    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n23.209  rustc            56645  56637    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.215  exe              56646  56620    0 /proc/1599/exe -exec-root=/var/run/docker fa2299019308ccdc0d053e4b83f0a87826a0d2c4c83ed0216afa2eb3c8314462 d7da31e8f8e1\n23.216  containerd-shim  56647  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b31584 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b delete\n23.219  runc             56660  56647    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b3158 --log-format json delete --force 8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b31584\n23.220  rustc            56661  56637    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n23.231  systemd-sysctl   56670  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth45545ef --prefix=/net/ipv4/neigh/veth45545ef --prefix=/net/ipv6/conf/veth45545ef --prefix=/net/ipv6/neigh/veth45545ef\n23.231  systemd-sysctl   56671  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth4312240 --prefix=/net/ipv4/neigh/veth4312240 --prefix=/net/ipv6/conf/veth4312240 --prefix=/net/ipv6/neigh/veth4312240\n23.236  exe              56673  1599     0 /proc/self/exe /var/run/docker/netns/c3ebc88a19aa all false\n23.255  execsnoop        56691  56636    0 /usr/local/bin/execsnoop -t\n23.255  python3          56691  56636    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n23.282  runc             56696  56610    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fa2299019308ccdc0d053e4b83f0a87826a0d2c4c83ed0216afa2eb3c83 --log-format json --systemd-cgroup start fa2299019308ccdc0d053e4b83f0a87826a0d2c4c83ed0216afa2eb3c8314462\n23.287  sh               56639  56610    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n23.288  cargo            56702  56639    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n23.298  cargo-native-tr  56702  56639    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n23.301  systemd-sysctl   56704  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha40893a --prefix=/net/ipv4/neigh/vetha40893a --prefix=/net/ipv6/conf/vetha40893a --prefix=/net/ipv6/neigh/vetha40893a\n23.301  systemd-sysctl   56703  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth60fc7e1 --prefix=/net/ipv4/neigh/veth60fc7e1 --prefix=/net/ipv6/conf/veth60fc7e1 --prefix=/net/ipv6/neigh/veth60fc7e1\n23.301  systemd-sysctl   56705  54510    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth84e20f5 --prefix=/net/ipv4/neigh/veth84e20f5 --prefix=/net/ipv6/conf/veth84e20f5 --prefix=/net/ipv6/neigh/veth84e20f5\n23.301  cargo            56706  56702    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n23.315  rustc            56707  56706    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.325  rustc            56709  56706    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n23.347  containerd-shim  56713  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id ce2f2e31920141e0611692e2e14efd73ae94254723b292c1b9729104af83a7e2 start\n23.350  containerd-shim  56720  56713    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id ce2f2e31920141e0611692e2e14efd73ae94254723b292c1b9729104af83a7e2 -address /var/run/docker/containerd/containerd.sock\n23.351  containerd-shim  56721  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 68355959d765aad8bf227fa53691f1da7c78466af4739606e5535912ada85424 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/68355959d765aad8bf227fa53691f1da7c78466af4739606e5535912ada delete\n23.353  runc             56736  56721    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/68355959d765aad8bf227fa53691f1da7c78466af4739606e5535912ada8542 --log-format json delete --force 68355959d765aad8bf227fa53691f1da7c78466af4739606e5535912ada85424\n23.354  runc             56737  56720    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ce2f2e31920141e0611692e2e14efd73ae94254723b292c1b9729104af8 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ce2f2e31920141e0611692e2e14efd73ae94254723b292c1b9729104af8 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ce2f2e31920141e0611692e2e14efd73ae94254723b292c1b9729104af8 ce2f2e31920141e0611692e2e14efd73ae94254723b292c1b9729104af83a7e2\n23.358  exe              56749  56737    0 /proc/self/exe init\n23.389  execsnoop        56758  56702    0 /usr/local/bin/execsnoop -t\n23.390  python3          56758  56702    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n23.391  exe              56761  56737    0 /proc/1599/exe -exec-root=/var/run/docker ce2f2e31920141e0611692e2e14efd73ae94254723b292c1b9729104af83a7e2 d7da31e8f8e1\n23.397  containerd-shim  56767  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 710f54f0e7966a1a1235ec45481be908847d35e1a959fb20faa0477f9e9cb902 start\n23.399  containerd-shim  56775  56767    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 710f54f0e7966a1a1235ec45481be908847d35e1a959fb20faa0477f9e9cb902 -address /var/run/docker/containerd/containerd.sock\n23.402  runc             56784  56775    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/710f54f0e7966a1a1235ec45481be908847d35e1a959fb20faa0477f9e9 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/710f54f0e7966a1a1235ec45481be908847d35e1a959fb20faa0477f9e9 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/710f54f0e7966a1a1235ec45481be908847d35e1a959fb20faa0477f9e9 710f54f0e7966a1a1235ec45481be908847d35e1a959fb20faa0477f9e9cb902\n23.407  exe              56791  56784    0 /proc/self/exe init\n23.411  exe              56794  1599     0 /proc/self/exe /var/run/docker/netns/f80d131f222c all false\n23.441  exe              56815  56784    0 /proc/1599/exe -exec-root=/var/run/docker 710f54f0e7966a1a1235ec45481be908847d35e1a959fb20faa0477f9e9cb902 d7da31e8f8e1\n23.464  exe              56822  1599     0 /proc/self/exe /var/run/docker/netns/b779c96be324 all false\n23.472  systemd-sysctl   56830  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth07c09c2 --prefix=/net/ipv4/neigh/veth07c09c2 --prefix=/net/ipv6/conf/veth07c09c2 --prefix=/net/ipv6/neigh/veth07c09c2\n23.496  runc             56841  56720    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ce2f2e31920141e0611692e2e14efd73ae94254723b292c1b9729104af8 --log-format json --systemd-cgroup start ce2f2e31920141e0611692e2e14efd73ae94254723b292c1b9729104af83a7e2\n23.501  sh               56752  56720    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n23.502  cargo            56847  56752    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n23.513  systemd-sysctl   56849  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth130827a --prefix=/net/ipv4/neigh/veth130827a --prefix=/net/ipv6/conf/veth130827a --prefix=/net/ipv6/neigh/veth130827a\n23.513  systemd-sysctl   56848  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth9e1ecf7 --prefix=/net/ipv4/neigh/veth9e1ecf7 --prefix=/net/ipv6/conf/veth9e1ecf7 --prefix=/net/ipv6/neigh/veth9e1ecf7\n23.514  cargo-native-tr  56847  56752    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n23.518  cargo            56850  56847    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n23.531  rustc            56851  56850    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.541  rustc            56853  56850    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n23.544  sh               56854  2147557   0 /bin/sh -c which ps\n23.545  which            56854  2147557   0 /usr/bin/which ps\n23.546  containerd-shim  56856  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id b96b8207cd81a2254bc1400c6e15807a463622df32a7150aaaa852eedbf2b6fa start\n23.547  runc             56858  56775    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/710f54f0e7966a1a1235ec45481be908847d35e1a959fb20faa0477f9e9 --log-format json --systemd-cgroup start 710f54f0e7966a1a1235ec45481be908847d35e1a959fb20faa0477f9e9cb902\n23.548  sh               56857  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n23.549  ps               56857  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n23.550  containerd-shim  56873  56856    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id b96b8207cd81a2254bc1400c6e15807a463622df32a7150aaaa852eedbf2b6fa -address /var/run/docker/containerd/containerd.sock\n23.553  sh               56808  56775    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n23.554  runc             56881  56873    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b96b8207cd81a2254bc1400c6e15807a463622df32a7150aaaa852eedbf --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b96b8207cd81a2254bc1400c6e15807a463622df32a7150aaaa852eedbf --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b96b8207cd81a2254bc1400c6e15807a463622df32a7150aaaa852eedbf b96b8207cd81a2254bc1400c6e15807a463622df32a7150aaaa852eedbf2b6fa\n23.554  cargo            56882  56808    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n23.560  exe              56889  56881    0 /proc/self/exe init\n23.567  cargo-native-tr  56882  56808    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n23.570  cargo            56892  56882    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n23.578  sh               56900  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n23.580  cpuUsage.sh      56900  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n23.581  sed              56901  56900    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n23.583  cat              56902  56900    0 /usr/bin/cat /proc/2240539/stat\n23.584  cat              56903  56900    0 /usr/bin/cat /proc/4193716/stat\n23.585  sleep            56904  56900    0 /usr/bin/sleep 1\n23.586  rustc            56905  56892    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.591  exe              56906  56881    0 /proc/1599/exe -exec-root=/var/run/docker b96b8207cd81a2254bc1400c6e15807a463622df32a7150aaaa852eedbf2b6fa d7da31e8f8e1\n23.596  rustc            56913  56892    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n23.616  execsnoop        56919  56847    0 /usr/local/bin/execsnoop -t\n23.616  python3          56919  56847    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n23.620  exe              56922  1599     0 /proc/self/exe /var/run/docker/netns/f8c58c9e3296 all false\n23.628  containerd-shim  56931  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9fd6e1207a55314adc77acbc5bf8d46c8cdc6d3aabaa60fc377a38b0626276c3 start\n23.631  containerd-shim  56938  56931    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 9fd6e1207a55314adc77acbc5bf8d46c8cdc6d3aabaa60fc377a38b0626276c3 -address /var/run/docker/containerd/containerd.sock\n23.634  execsnoop        56947  56882    0 /usr/local/bin/execsnoop -t\n23.634  python3          56947  56882    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n23.635  runc             56951  56938    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9fd6e1207a55314adc77acbc5bf8d46c8cdc6d3aabaa60fc377a38b0626 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9fd6e1207a55314adc77acbc5bf8d46c8cdc6d3aabaa60fc377a38b0626 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9fd6e1207a55314adc77acbc5bf8d46c8cdc6d3aabaa60fc377a38b0626 9fd6e1207a55314adc77acbc5bf8d46c8cdc6d3aabaa60fc377a38b0626276c3\n23.646  exe              56959  56951    0 /proc/self/exe init\n23.667  runc             56969  56873    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b96b8207cd81a2254bc1400c6e15807a463622df32a7150aaaa852eedbf --log-format json --systemd-cgroup start b96b8207cd81a2254bc1400c6e15807a463622df32a7150aaaa852eedbf2b6fa\n23.672  sh               56894  56873    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n23.673  cargo            56975  56894    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n23.676  exe              56976  56951    0 /proc/1599/exe -exec-root=/var/run/docker 9fd6e1207a55314adc77acbc5bf8d46c8cdc6d3aabaa60fc377a38b0626276c3 d7da31e8f8e1\n23.685  cargo-native-tr  56975  56894    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n23.688  cargo            56983  56975    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n23.699  rustc            56986  56983    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.703  exe              56987  1599     0 /proc/self/exe /var/run/docker/netns/1cadc37f4aa7 all false\n"
}
```

#### Record 33

```json
{
  "argv": [
    "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52250,
  "build_script_target_dir": "libc-c3c858474dcfa7e6",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build",
  "pid": 52250,
  "ppid": 51706,
  "root_cargo_pid": 51706,
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
  "build_script_root_pid": 52250,
  "build_script_target_dir": "libc-c3c858474dcfa7e6",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 52251,
  "ppid": 52250,
  "root_cargo_pid": 51706,
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
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/ring-36133a68ed4b831a/build-script-build",
  "pid": 52530,
  "ppid": 51706,
  "root_cargo_pid": 51706,
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
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-E",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/11703895368463712161detect_compiler_family.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52531,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-quiet",
    "-imultiarch",
    "aarch64-linux-gnu",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/11703895368463712161detect_compiler_family.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52532,
  "ppid": 52531,
  "root_cargo_pid": 51706,
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
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52534,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52538,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/curve25519/curve25519.c",
    "-quiet",
    "-dumpbase",
    "curve25519.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/fad98b632b8ce3cc-curve25519.o",
    "-gdwarf-4",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52539,
  "ppid": 52538,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/fad98b632b8ce3cc-curve25519.o",
    "/tmp/cczdXGOR.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52561,
  "ppid": 52538,
  "root_cargo_pid": 51706,
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
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52572,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/aes/aes_nohw.c",
    "-quiet",
    "-dumpbase",
    "aes_nohw.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca4b6ef5433f5aeb-aes_nohw.o",
    "-gdwarf-4",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52573,
  "ppid": 52572,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca4b6ef5433f5aeb-aes_nohw.o",
    "/tmp/cc68yptr.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52580,
  "ppid": 52572,
  "root_cargo_pid": 51706,
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
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52583,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/bn/montgomery.c",
    "-quiet",
    "-dumpbase",
    "montgomery.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca8bd8684bb569fa-montgomery.o",
    "-gdwarf-4",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52585,
  "ppid": 52583,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca8bd8684bb569fa-montgomery.o",
    "/tmp/ccDXG3Ti.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52593,
  "ppid": 52583,
  "root_cargo_pid": 51706,
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
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52603,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/bn/montgomery_inv.c",
    "-quiet",
    "-dumpbase",
    "montgomery_inv.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca8bd8684bb569fa-montgomery_inv.o",
    "-gdwarf-4",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52607,
  "ppid": 52603,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca8bd8684bb569fa-montgomery_inv.o",
    "/tmp/cc5yfwUN.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52616,
  "ppid": 52603,
  "root_cargo_pid": 51706,
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
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52620,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/ecp_nistz.c",
    "-quiet",
    "-dumpbase",
    "ecp_nistz.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-ecp_nistz.o",
    "-gdwarf-4",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52624,
  "ppid": 52620,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-ecp_nistz.o",
    "/tmp/ccTv4TO3.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52630,
  "ppid": 52620,
  "root_cargo_pid": 51706,
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
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52632,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/gfp_p256.c",
    "-quiet",
    "-dumpbase",
    "gfp_p256.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-gfp_p256.o",
    "-gdwarf-4",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52633,
  "ppid": 52632,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-gfp_p256.o",
    "/tmp/ccYu76h1.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52634,
  "ppid": 52632,
  "root_cargo_pid": 51706,
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
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52637,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/gfp_p384.c",
    "-quiet",
    "-dumpbase",
    "gfp_p384.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-gfp_p384.o",
    "-gdwarf-4",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52638,
  "ppid": 52637,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-gfp_p384.o",
    "/tmp/cciBg9dn.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52644,
  "ppid": 52637,
  "root_cargo_pid": 51706,
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
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52646,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/p256.c",
    "-quiet",
    "-dumpbase",
    "p256.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-p256.o",
    "-gdwarf-4",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52647,
  "ppid": 52646,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-p256.o",
    "/tmp/ccwGTM72.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52648,
  "ppid": 52646,
  "root_cargo_pid": 51706,
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
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52653,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/limbs/limbs.c",
    "-quiet",
    "-dumpbase",
    "limbs.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a1949f2101df4b9c-limbs.o",
    "-gdwarf-4",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52654,
  "ppid": 52653,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a1949f2101df4b9c-limbs.o",
    "/tmp/ccA9Bm5z.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52658,
  "ppid": 52653,
  "root_cargo_pid": 51706,
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
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52659,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/mem.c",
    "-quiet",
    "-dumpbase",
    "mem.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-mem.o",
    "-gdwarf-4",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52660,
  "ppid": 52659,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-mem.o",
    "/tmp/ccZb5VZZ.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52661,
  "ppid": 52659,
  "root_cargo_pid": 51706,
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
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52662,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/poly1305/poly1305.c",
    "-quiet",
    "-dumpbase",
    "poly1305.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/bec76f70393ddef1-poly1305.o",
    "-gdwarf-4",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52663,
  "ppid": 52662,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/bec76f70393ddef1-poly1305.o",
    "/tmp/ccgsTPMd.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52664,
  "ppid": 52662,
  "root_cargo_pid": 51706,
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
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52665,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/crypto.c",
    "-quiet",
    "-dumpbase",
    "crypto.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-crypto.o",
    "-gdwarf-4",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52666,
  "ppid": 52665,
  "root_cargo_pid": 51706,
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

#### Record 74

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-crypto.o",
    "/tmp/ccOHzoxr.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52667,
  "ppid": 52665,
  "root_cargo_pid": 51706,
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

#### Record 75

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52668,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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

#### Record 76

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/p256-nistz.c",
    "-quiet",
    "-dumpbase",
    "p256-nistz.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-p256-nistz.o",
    "-gdwarf-4",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52669,
  "ppid": 52668,
  "root_cargo_pid": 51706,
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

#### Record 77

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-p256-nistz.o",
    "/tmp/ccCQGcRG.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52686,
  "ppid": 52668,
  "root_cargo_pid": 51706,
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

#### Record 78

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52687,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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

#### Record 79

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/aesv8-armx-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52688,
  "ppid": 52687,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "--gdwarf2",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-aesv8-armx-linux64.o",
    "/tmp/cc11RF9a.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52689,
  "ppid": 52687,
  "root_cargo_pid": 51706,
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

#### Record 81

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52690,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/ghashv8-armx-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52691,
  "ppid": 52690,
  "root_cargo_pid": 51706,
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

#### Record 83

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "--gdwarf2",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-ghashv8-armx-linux64.o",
    "/tmp/ccMQyQQn.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52692,
  "ppid": 52690,
  "root_cargo_pid": 51706,
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

#### Record 84

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52693,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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

#### Record 85

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/chacha-armv8-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52694,
  "ppid": 52693,
  "root_cargo_pid": 51706,
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

#### Record 86

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "--gdwarf2",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-chacha-armv8-linux64.o",
    "/tmp/ccQQKu1z.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52695,
  "ppid": 52693,
  "root_cargo_pid": 51706,
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

#### Record 87

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52696,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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

#### Record 88

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/chacha20_poly1305_armv8-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52697,
  "ppid": 52696,
  "root_cargo_pid": 51706,
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

#### Record 89

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "--gdwarf2",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-chacha20_poly1305_armv8-linux64.o",
    "/tmp/ccteYgTP.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52698,
  "ppid": 52696,
  "root_cargo_pid": 51706,
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

#### Record 90

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52699,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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

#### Record 91

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/vpaes-armv8-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52700,
  "ppid": 52699,
  "root_cargo_pid": 51706,
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

#### Record 92

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "--gdwarf2",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-vpaes-armv8-linux64.o",
    "/tmp/ccQag2N4.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52701,
  "ppid": 52699,
  "root_cargo_pid": 51706,
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

#### Record 93

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52702,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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

#### Record 94

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/armv8-mont-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52707,
  "ppid": 52702,
  "root_cargo_pid": 51706,
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

#### Record 95

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "--gdwarf2",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-armv8-mont-linux64.o",
    "/tmp/ccLRjINh.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52708,
  "ppid": 52702,
  "root_cargo_pid": 51706,
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

#### Record 96

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52713,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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

#### Record 97

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/p256-armv8-asm-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52714,
  "ppid": 52713,
  "root_cargo_pid": 51706,
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

#### Record 98

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "--gdwarf2",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-p256-armv8-asm-linux64.o",
    "/tmp/cckXcfa5.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52715,
  "ppid": 52713,
  "root_cargo_pid": 51706,
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

#### Record 99

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52716,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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

#### Record 100

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/ghash-neon-armv8-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52717,
  "ppid": 52716,
  "root_cargo_pid": 51706,
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

#### Record 101

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "--gdwarf2",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-ghash-neon-armv8-linux64.o",
    "/tmp/ccAnp4Mm.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52718,
  "ppid": 52716,
  "root_cargo_pid": 51706,
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

#### Record 102

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52719,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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

#### Record 103

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/aesv8-gcm-armv8-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52720,
  "ppid": 52719,
  "root_cargo_pid": 51706,
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

#### Record 104

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "--gdwarf2",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-aesv8-gcm-armv8-linux64.o",
    "/tmp/ccGEexmz.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52721,
  "ppid": 52719,
  "root_cargo_pid": 51706,
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

#### Record 105

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52722,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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

#### Record 106

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/sha512-armv8-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52723,
  "ppid": 52722,
  "root_cargo_pid": 51706,
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

#### Record 107

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "--gdwarf2",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-sha512-armv8-linux64.o",
    "/tmp/ccj7W6hN.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52724,
  "ppid": 52722,
  "root_cargo_pid": 51706,
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

#### Record 108

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52731,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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

#### Record 109

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/sha256-armv8-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52733,
  "ppid": 52731,
  "root_cargo_pid": 51706,
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

#### Record 110

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "--gdwarf2",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-sha256-armv8-linux64.o",
    "/tmp/ccPck4cr.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52741,
  "ppid": 52731,
  "root_cargo_pid": 51706,
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

#### Record 111

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cq",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/libring_core_0_17_8_.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/fad98b632b8ce3cc-curve25519.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca4b6ef5433f5aeb-aes_nohw.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca8bd8684bb569fa-montgomery.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca8bd8684bb569fa-montgomery_inv.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-ecp_nistz.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-gfp_p256.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-gfp_p384.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-p256.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a1949f2101df4b9c-limbs.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-mem.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/bec76f70393ddef1-poly1305.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-crypto.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-p256-nistz.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-aesv8-armx-linux64.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-ghashv8-armx-linux64.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-chacha-armv8-linux64.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-chacha20_poly1305_armv8-linux64.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 52743,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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

#### Record 112

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "s",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/libring_core_0_17_8_.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 52746,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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

#### Record 113

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-E",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/810360224297801178detect_compiler_family.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52750,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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

#### Record 114

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-quiet",
    "-imultiarch",
    "aarch64-linux-gnu",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/810360224297801178detect_compiler_family.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52754,
  "ppid": 52750,
  "root_cargo_pid": 51706,
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

#### Record 115

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52757,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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

#### Record 116

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "-Wcast-qual",
    "-Wconversion",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 52758,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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

#### Record 117

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/constant_time_test.c",
    "-quiet",
    "-dumpbase",
    "constant_time_test.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-constant_time_test.o",
    "-gdwarf-4",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 52761,
  "ppid": 52758,
  "root_cargo_pid": 51706,
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

#### Record 118

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-constant_time_test.o",
    "/tmp/ccNO11ax.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 52764,
  "ppid": 52758,
  "root_cargo_pid": 51706,
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

#### Record 119

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cq",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/libring_core_0_17_8_test.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-constant_time_test.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 52767,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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

#### Record 120

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "s",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/libring_core_0_17_8_test.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52530,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 52768,
  "ppid": 52530,
  "root_cargo_pid": 51706,
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

#### Record 121

```json
{
  "argv": [
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52773,
  "build_script_target_dir": "rustls-2216ddcaf0bdcdf8",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build-script-build",
  "pid": 52773,
  "ppid": 51706,
  "root_cargo_pid": 51706,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "_build_script_out_dir": "/target/debug/build/rustls-2216ddcaf0bdcdf8/out"
}
```

#### Record 122

```json
{
  "crate": "rustls",
  "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "event_id": "bsrun:357ca8740a0588d9:aa8e620880ea118c:01382d2620d23103",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
  "out_dir": "/target/debug/build/rustls-2216ddcaf0bdcdf8/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
  "success": true,
  "target": null,
  "version": "0.21.12",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
    "source": "cwd_prefix"
  }
}
```

#### Record 123

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

#### Record 124

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

#### Record 125

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52250,
  "build_script_target_dir": "libc-c3c858474dcfa7e6",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 52251,
  "ppid": 52250,
  "root_cargo_pid": 51706,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 126

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/curve25519/curve25519.c",
    "-quiet",
    "-dumpbase",
    "curve25519.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/fad98b632b8ce3cc-curve25519.o",
    "-gdwarf-4",
    "..."
  ],
  "src": "crypto/curve25519/curve25519.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/fad98b632b8ce3cc-curve25519.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52539,
  "ppid": 52538,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 127

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/aes/aes_nohw.c",
    "-quiet",
    "-dumpbase",
    "aes_nohw.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca4b6ef5433f5aeb-aes_nohw.o",
    "-gdwarf-4",
    "..."
  ],
  "src": "crypto/fipsmodule/aes/aes_nohw.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca4b6ef5433f5aeb-aes_nohw.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52573,
  "ppid": 52572,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 128

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/bn/montgomery.c",
    "-quiet",
    "-dumpbase",
    "montgomery.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca8bd8684bb569fa-montgomery.o",
    "-gdwarf-4",
    "..."
  ],
  "src": "crypto/fipsmodule/bn/montgomery.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca8bd8684bb569fa-montgomery.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52585,
  "ppid": 52583,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 129

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/bn/montgomery_inv.c",
    "-quiet",
    "-dumpbase",
    "montgomery_inv.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca8bd8684bb569fa-montgomery_inv.o",
    "-gdwarf-4",
    "..."
  ],
  "src": "crypto/fipsmodule/bn/montgomery_inv.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca8bd8684bb569fa-montgomery_inv.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52607,
  "ppid": 52603,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 130

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/ecp_nistz.c",
    "-quiet",
    "-dumpbase",
    "ecp_nistz.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-ecp_nistz.o",
    "-gdwarf-4",
    "..."
  ],
  "src": "crypto/fipsmodule/ec/ecp_nistz.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-ecp_nistz.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52624,
  "ppid": 52620,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 131

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/gfp_p256.c",
    "-quiet",
    "-dumpbase",
    "gfp_p256.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-gfp_p256.o",
    "-gdwarf-4",
    "..."
  ],
  "src": "crypto/fipsmodule/ec/gfp_p256.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-gfp_p256.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52633,
  "ppid": 52632,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 132

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/gfp_p384.c",
    "-quiet",
    "-dumpbase",
    "gfp_p384.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-gfp_p384.o",
    "-gdwarf-4",
    "..."
  ],
  "src": "crypto/fipsmodule/ec/gfp_p384.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-gfp_p384.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52638,
  "ppid": 52637,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 133

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/p256.c",
    "-quiet",
    "-dumpbase",
    "p256.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-p256.o",
    "-gdwarf-4",
    "..."
  ],
  "src": "crypto/fipsmodule/ec/p256.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-p256.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52647,
  "ppid": 52646,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 134

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/limbs/limbs.c",
    "-quiet",
    "-dumpbase",
    "limbs.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a1949f2101df4b9c-limbs.o",
    "-gdwarf-4",
    "..."
  ],
  "src": "crypto/limbs/limbs.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a1949f2101df4b9c-limbs.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52654,
  "ppid": 52653,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 135

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/mem.c",
    "-quiet",
    "-dumpbase",
    "mem.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-mem.o",
    "-gdwarf-4",
    "..."
  ],
  "src": "crypto/mem.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-mem.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52660,
  "ppid": 52659,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 136

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/poly1305/poly1305.c",
    "-quiet",
    "-dumpbase",
    "poly1305.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/bec76f70393ddef1-poly1305.o",
    "-gdwarf-4",
    "..."
  ],
  "src": "crypto/poly1305/poly1305.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/bec76f70393ddef1-poly1305.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52663,
  "ppid": 52662,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 137

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/crypto.c",
    "-quiet",
    "-dumpbase",
    "crypto.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-crypto.o",
    "-gdwarf-4",
    "..."
  ],
  "src": "crypto/crypto.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-crypto.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52666,
  "ppid": 52665,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 138

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/p256-nistz.c",
    "-quiet",
    "-dumpbase",
    "p256-nistz.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-p256-nistz.o",
    "-gdwarf-4",
    "..."
  ],
  "src": "crypto/fipsmodule/ec/p256-nistz.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-p256-nistz.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52669,
  "ppid": 52668,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 139

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/aesv8-armx-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "src": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/aesv8-armx-linux64.S",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-aesv8-armx-linux64.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52688,
  "ppid": 52687,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 140

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/ghashv8-armx-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "src": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/ghashv8-armx-linux64.S",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-ghashv8-armx-linux64.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52691,
  "ppid": 52690,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 141

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/chacha-armv8-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "src": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/chacha-armv8-linux64.S",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-chacha-armv8-linux64.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52694,
  "ppid": 52693,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 142

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/chacha20_poly1305_armv8-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "src": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/chacha20_poly1305_armv8-linux64.S",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-chacha20_poly1305_armv8-linux64.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52697,
  "ppid": 52696,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 143

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/vpaes-armv8-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "src": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/vpaes-armv8-linux64.S",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-vpaes-armv8-linux64.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52700,
  "ppid": 52699,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 144

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/armv8-mont-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "src": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/armv8-mont-linux64.S",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-armv8-mont-linux64.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52707,
  "ppid": 52702,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 145

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/p256-armv8-asm-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "src": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/p256-armv8-asm-linux64.S",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-p256-armv8-asm-linux64.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52714,
  "ppid": 52713,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 146

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/ghash-neon-armv8-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "src": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/ghash-neon-armv8-linux64.S",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-ghash-neon-armv8-linux64.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52717,
  "ppid": 52716,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 147

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/aesv8-gcm-armv8-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "src": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/aesv8-gcm-armv8-linux64.S",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-aesv8-gcm-armv8-linux64.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52720,
  "ppid": 52719,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 148

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/sha512-armv8-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "src": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/sha512-armv8-linux64.S",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-sha512-armv8-linux64.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52723,
  "ppid": 52722,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 149

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/sha256-armv8-linux64.S",
    "-mlittle-endian",
    "-mabi=lp64",
    "-std=c11",
    "-Wextra",
    "-Wall",
    "-Wbad-function-cast",
    "..."
  ],
  "src": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/sha256-armv8-linux64.S",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-sha256-armv8-linux64.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52733,
  "ppid": 52731,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 150

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/constant_time_test.c",
    "-quiet",
    "-dumpbase",
    "constant_time_test.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-constant_time_test.o",
    "-gdwarf-4",
    "..."
  ],
  "src": "crypto/constant_time_test.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-constant_time_test.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52761,
  "ppid": 52758,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 151

```json
{
  "event": "archive",
  "tool": "/usr/bin/aarch64-linux-gnu-ar",
  "real_tool": "/usr/bin/aarch64-linux-gnu-ar",
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cq",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/libring_core_0_17_8_.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/fad98b632b8ce3cc-curve25519.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca4b6ef5433f5aeb-aes_nohw.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca8bd8684bb569fa-montgomery.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca8bd8684bb569fa-montgomery_inv.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-ecp_nistz.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-gfp_p256.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-gfp_p384.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-p256.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a1949f2101df4b9c-limbs.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-mem.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/bec76f70393ddef1-poly1305.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-crypto.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-p256-nistz.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-aesv8-armx-linux64.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-ghashv8-armx-linux64.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-chacha-armv8-linux64.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-chacha20_poly1305_armv8-linux64.o",
    "..."
  ],
  "archive": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/libring_core_0_17_8_.a",
  "objects": [
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/fad98b632b8ce3cc-curve25519.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca4b6ef5433f5aeb-aes_nohw.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca8bd8684bb569fa-montgomery.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca8bd8684bb569fa-montgomery_inv.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-ecp_nistz.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-gfp_p256.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-gfp_p384.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-p256.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a1949f2101df4b9c-limbs.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-mem.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/bec76f70393ddef1-poly1305.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-crypto.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-p256-nistz.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-aesv8-armx-linux64.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-ghashv8-armx-linux64.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-chacha-armv8-linux64.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-chacha20_poly1305_armv8-linux64.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": true,
  "pid": 52743,
  "ppid": 52530,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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

#### Record 152

```json
{
  "event": "archive",
  "tool": "/usr/bin/aarch64-linux-gnu-ar",
  "real_tool": "/usr/bin/aarch64-linux-gnu-ar",
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cq",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/libring_core_0_17_8_test.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-constant_time_test.o"
  ],
  "archive": "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/libring_core_0_17_8_test.a",
  "objects": [
    "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-constant_time_test.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 52767,
  "ppid": 52530,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51706,
  "build_script_root_pid": 52530,
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
  "time": "2026-07-14T01:33:28.306865+00:00",
  "crate": "rustls",
  "version": "0.21.12",
  "architecture": "aarch64",
  "duration_seconds": 33.716127320658416,
  "trace_record_count": 124,
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
        "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
        "manifest_path": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12/Cargo.toml"
      }
    ],
    "attributed_event_count": 33,
    "unattributed_event_count": 91,
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
      "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
      "workspace_root": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12"
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
          "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
          "name": "rustls",
          "version": "0.21.12",
          "manifest_path": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12"
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
        "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
      "exit_code": 0,
      "kind": "exec",
      "pid": 51913,
      "ppid": 51832,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
      "event_id": "used:cc:c42419fcc1bb316a:fab8fe6a994f4e05:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
      "pid": 51913,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
      "event_id": "used:cc:c42419fcc1bb316a:9c396efe95e3798a:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
      "pid": 51913,
      "sha256": "c6eaa5a3126fd4f5af824fad2289d1dba511352408a2c76327fffa9a2bbf1118",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
      "event_id": "used:cc:c42419fcc1bb316a:81133837f6ebb247:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
      "pid": 51913,
      "sha256": "9532727822144c0567ab989f643960e118eeef51d0b03f45a33a5d24fde31d49",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
      "event_id": "used:cc:c42419fcc1bb316a:8ecaed9234a82d15:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
      "pid": 51913,
      "sha256": "c926f0d80b9db98309ea373d7d925d16448fdd102cdaa73601edda00562f8a30",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
      "event_id": "used:cc:c42419fcc1bb316a:2c99fba7eefc3c38:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
      "pid": 51913,
      "sha256": "7f033c8e48115010e778ebb040c38069ea3eccabb0d9630fec159b11bde2b2f8",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
      "event_id": "used:cc:c42419fcc1bb316a:6b7214eb8cbc327c:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
      "pid": 51913,
      "sha256": "9d068557d15915decb6945225220ee80a4167b5a2ff586bad30f9d19f74a97c4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
      "event_id": "used:cc:c42419fcc1bb316a:4193d58c6908a17d:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
      "pid": 51913,
      "sha256": "2a6cf24c0a0269e4833fdfcff9cd095c0e58be7a7e310e83ace955edb2ba5340",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
      "cargo_pkg_name": "rustls",
      "cargo_pkg_version": "0.21.12",
      "context_path": "/tmp/native-trace-50494-1783992780436/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-50494-1783992780436/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 51913,
      "ppid": 51832,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM",
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
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustc3mUgmM/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.1xy5h4s.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.1xy5h4s.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.1xy5h4s.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.1xy5h4s.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.1xy5h4s.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.1xy5h4s.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-51913-1783992784680408562.map",
      "pid": 51913,
      "ppid": 51832,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-51913-1783992784680408562.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/raw-dylibs",
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
      "pid": 52137,
      "ppid": 51818,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/raw-dylibs",
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
      "event_id": "used:cc:b47364ada97c6bc2:c6dea2fad6a37f38:6abd7aadaee76ef4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
      "pid": 52137,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/raw-dylibs",
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
      "pid": 52137,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/raw-dylibs",
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
      "pid": 52137,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/raw-dylibs",
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
      "pid": 52137,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/raw-dylibs",
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
      "pid": 52137,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/raw-dylibs",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/raw-dylibs",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/raw-dylibs",
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
      "context_path": "/tmp/native-trace-50494-1783992780436/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-50494-1783992780436/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 52137,
      "ppid": 51818,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/raw-dylibs",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk",
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
          "directory": "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk",
          "kind": "object",
          "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustckuU3mk/symbols.o",
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
      "map_path": "/tmp/native-trace-link-cc-52137-1783992785012666856.map",
      "pid": 52137,
      "ppid": 51818,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-52137-1783992785012666856.map"
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/raw-dylibs",
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
      "pid": 52496,
      "ppid": 52455,
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/raw-dylibs",
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
      "event_id": "used:cc:d3ed579287892b7b:23a293744c001c76:0983853cb5c6903e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
      "path": "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
      "pid": 52496,
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/raw-dylibs",
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
      "pid": 52496,
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/raw-dylibs",
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
      "pid": 52496,
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/raw-dylibs",
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
      "pid": 52496,
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/raw-dylibs",
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
      "pid": 52496,
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/raw-dylibs",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/raw-dylibs",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/raw-dylibs",
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
      "context_path": "/tmp/native-trace-50494-1783992780436/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-50494-1783992780436/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 52496,
      "ppid": 52455,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/raw-dylibs",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG",
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
          "directory": "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG",
          "kind": "object",
          "path": "/target/debug/build/ring-36133a68ed4b831a/rustcasFWnG/symbols.o",
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
      "map_path": "/tmp/native-trace-link-cc-52496-1783992786109873056.map",
      "pid": 52496,
      "ppid": 52455,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-52496-1783992786109873056.map"
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
      "parse_error_count": 2,
      "parsed_event_count": 940,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 942,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "47  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name valuable --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n19.381  cargo            55059  54870    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n19.394  rustc            55070  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n19.419  rustc            55113  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n19.420  rustc            55111  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.18/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=ba1b82e103e0280b ...\n19.518  cc               55188  55113    0 /tmp/native-trace-54870-1783992801742/shims/cc -m64 /target/debug/build/proc-macro2-46239aad0aaf2dde/rustcz8FJmv/symbols.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0bv3et31ep2k9sd4r4xv6yltt.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0edhhq7oafgl2yf0nrxumcg9r.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0g0902jm3uya6wioho7beok0j.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0owef7ksnbk6ukcc2242nefkr.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0rdzizyhqamtksvgo7enpq5az.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1r69zij4wcxunk2gd17a0kpg6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1sghvgwc08k4idxie37yo3pw0.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1wbfjtyvleo9dhvql6dw9ezks.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2om80ctxk1ydfs1240ujhhg0b.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2ylb2sbb9n609gy1nl3eivm1m.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.34jg2bcz8z6kfpvajxful9pig.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3dgkawms7tf7icnefiv8uh2ur.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3h5kxyomdhio13fti327b3ul4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3pfht32bkan9uc6xs96laffv6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3vy5vc4kvl4zobt41ffusuic4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3wfb4bv7o9ei3djc1ma3hgool.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.4sen9su2ywavj025286hzh4rs.0uq14k2.rcgu.o ...\n19.519  cc               55189  55188    0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-46239aad0aaf2dde/rustcz8FJmv/symbols.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0bv3et31ep2k9sd4r4xv6yltt.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0edhhq7oafgl2yf0nrxumcg9r.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0g0902jm3uya6wioho7beok0j.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0owef7ksnbk6ukcc2242nefkr.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0rdzizyhqamtksvgo7enpq5az.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1r69zij4wcxunk2gd17a0kpg6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1sghvgwc08k4idxie37yo3pw0.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1wbfjtyvleo9dhvql6dw9ezks.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2om80ctxk1ydfs1240ujhhg0b.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2ylb2sbb9n609gy1nl3eivm1m.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.34jg2bcz8z6kfpvajxful9pig.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3dgkawms7tf7icnefiv8uh2ur.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3h5kxyomdhio13fti327b3ul4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3pfht32bkan9uc6xs96laffv6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3vy5vc4kvl4zobt41ffusuic4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3wfb4bv7o9ei3djc1ma3hgool.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.4sen9su2ywavj025286hzh4rs.0uq14k2.rcgu.o ...\n19.523  collect2         55190  55189    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.524  ld.lld           55191  55190    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde ...\n19.526  rust-lld         55191  55190    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.580  sed              55209  54989    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n19.580  build-script-bu  55210  55059    0 /target/debug/build/proc-macro2-46239aad0aaf2dde/build-script-build\n19.582  cat              55211  54989    0 /usr/bin/cat /proc/2240539/stat\n19.582  rustc            55212  55210    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n19.583  cat              55214  54989    0 /usr/bin/cat /proc/4193716/stat\n19.592  rustc            55217  55210    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-1a2ad12dc9160ce7/out/probe build/probe.rs --target aarch64-unknown-linux-gnu\n19.619  rustc            55222  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n20.184  cross            55331  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.185  rustc            55334  55331    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.206  rustc            55334  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.218  rustc            55346  55331    0 /home/xmoe/.cargo/bin/rustc -vV\n20.240  rustc            55346  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.250  cargo            55356  55331    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.271  cargo            55356  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.281  rustc            55366  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.283  git              55365  2235138   0 /usr/bin/git config --get commit.template\n20.290  rustc            55368  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.298  git              55369  2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n20.301  rustc            55373  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.314  git              55374  2235138   0 /usr/bin/git status -z -uall\n20.326  rustc            55379  55331    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n20.330  git              55378  2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n20.348  rustc            55379  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n20.360  docker           55391  55331    0 /usr/bin/docker --help\n20.371  docker           55402  55331    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n20.383  runc             55412  1599     0 /usr/bin/runc --version\n20.386  docker-init      55418  1599     0 /usr/bin/docker-init --version\n20.387  docker           55419  55331    0 /usr/bin/docker info -f {{.SecurityOptions}}\n20.398  runc             55430  1599     0 /usr/bin/runc --version\n20.401  docker-init      55436  1599     0 /usr/bin/docker-init --version\n20.422  rustup           55440  55331    0 /home/xmoe/.cargo/bin/rustup toolchain list\n20.443  rustup           55449  55331    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n20.464  rustup           55458  55331    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n20.488  uname            55467  55331    0 /usr/bin/uname -r\n20.503  docker           55468  55331    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n20.540  systemd-sysctl   55483  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8170368 --prefix=/net/ipv4/neigh/veth8170368 --prefix=/net/ipv6/conf/veth8170368 --prefix=/net/ipv6/neigh/veth8170368\n20.540  systemd-sysctl   55482  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth81dd9a9 --prefix=/net/ipv4/neigh/veth81dd9a9 --prefix=/net/ipv6/conf/veth81dd9a9 --prefix=/net/ipv6/neigh/veth81dd9a9\n20.553  containerd-shim  55484  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 start\n20.556  containerd-shim  55491  1        0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 -address /var/run/docker/containerd/containerd.sock\n20.560  runc             55501  55491    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956\n20.565  exe              55509  55501    0 /proc/self/exe init\n20.583  cross            55513  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n20.584  rustc            55520  55513    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.589  rustc            55520  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.598  exe              55532  55501    0 /proc/1599/exe -exec-root=/var/run/docker 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 d7da31e8f8e1\n20.600  rustc            55539  55513    0 /home/xmoe/.cargo/bin/rustc -vV\n20.605  rustc            55539  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.610  cross            55549  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n20.612  rustc            55552  55549    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.614  cargo            55561  55513    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.615  cross            55564  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.616  rustc            55567  55564    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.618  exe              55576  1599     0 /proc/self/exe /var/run/docker/netns/8b628a44607d all false\n20.620  cargo            55561  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.621  rustc            55567  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.630  rustc            55596  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.633  rustc            55597  55564    0 /home/xmoe/.cargo/bin/rustc -vV\n20.637  rustc            55552  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.638  rustc            55597  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.639  rustc            55607  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.646  cargo            55614  55564    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.649  rustc            55616  55549    0 /home/xmoe/.cargo/bin/rustc -vV\n20.650  rustc            55625  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.652  cargo            55614  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.662  rustc            55637  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.664  runc             55639  55491    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --log-format json --systemd-cgroup start 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956\n20.669  sh               55511  55491    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n20.670  cargo            55646  55511    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n20.672  rustc            55647  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.675  rustc            55616  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.683  cargo-native-tr  55646  55511    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n20.683  cargo            55652  55549    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.684  rustc            55653  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.686  cargo            55654  55646    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n20.696  rustc            55666  55654    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.705  cargo            55652  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.708  rustc            55668  55654    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.716  rustc            55670  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.725  rustc            55674  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.737  rustc            55678  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.773  git              55683  2235138   0 /usr/bin/git worktree list --porcelain\n20.811  cross            55684  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n20.812  rustc            55687  55684    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.817  rustc            55687  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.828  runc             55701  47737    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a --log-format json --systemd-cgroup kill --all 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9 9\n20.828  rustc            55700  55684    0 /home/xmoe/.cargo/bin/rustc -vV\n20.833  rustc            55700  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.842  cargo            55716  55684    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n20.845  runc             55725  47737    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a --log-format json --systemd-cgroup delete 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9\n20.847  cargo            55716  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n20.857  rustc            55731  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.866  rustc            55733  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.889  rustc            55737  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.974  runc             55741  49799    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e --log-format json --systemd-cgroup kill --all f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e 9\n20.982  runc             55748  49799    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e --log-format json --systemd-cgroup delete f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e\n21.061  containerd-shim  55754  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a delete\n21.064  runc             55761  55754    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a --log-format json delete --force 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9\n21.067  runc             55767  50023    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc --log-format json --systemd-cgroup kill --all a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0 9\n21.083  runc             55773  50023    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc --log-format json --systemd-cgroup delete a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0\n21.105  systemd-sysctl   55779  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethae76c09 --prefix=/net/ipv4/neigh/vethae76c09 --prefix=/net/ipv6/conf/vethae76c09 --prefix=/net/ipv6/neigh/vethae76c09\n21.168  runc             55780  50289    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d67 --log-format json --systemd-cgroup kill --all 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb 9\n21.185  runc             55786  50289    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d67 --log-format json --systemd-cgroup delete 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb\n21.217  cross            55792  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n21.218  rustc            55795  55792    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.223  rustc            55795  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.234  rustc            55807  55792    0 /home/xmoe/.cargo/bin/rustc -vV\n21.239  rustc            55807  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.242  containerd-shim  55816  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e delete\n21.244  runc             55822  55816    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1 --log-format json delete --force f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e\n21.247  cross            55829  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n21.248  rustc            55832  55829    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.248  cargo            55833  55792    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.252  rustc            55832  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.252  cargo            55833  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.263  rustc            55853  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.264  rustc            55854  55829    0 /home/xmoe/.cargo/bin/rustc -vV\n21.269  rustc            55854  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.271  rustc            55864  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.278  cargo            55869  55829    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.280  systemd-sysctl   55870  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethddd6c57 --prefix=/net/ipv4/neigh/vethddd6c57 --prefix=/net/ipv6/conf/vethddd6c57 --prefix=/net/ipv6/neigh/vethddd6c57\n21.282  containerd-shim  55880  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc delete\n21.283  rustc            55884  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.284  cargo            55869  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.284  runc             55887  55880    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f --log-format json delete --force a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0\n21.293  rustc            55896  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.303  rustc            55898  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.314  rustc            55902  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.322  systemd-sysctl   55903  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf192d49 --prefix=/net/ipv4/neigh/vethf192d49 --prefix=/net/ipv6/conf/vethf192d49 --prefix=/net/ipv6/neigh/vethf192d49\n21.409  containerd-shim  55908  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d67 delete\n21.411  runc             55915  55908    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7c --log-format json delete --force 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb\n21.443  systemd-sysctl   55920  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7b4cddd --prefix=/net/ipv4/neigh/veth7b4cddd --prefix=/net/ipv6/conf/veth7b4cddd --prefix=/net/ipv6/neigh/veth7b4cddd\n22.580  rustc            55925  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.629  rustc            55927  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.657  rustc            55929  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.704  rustc            55931  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.755  rustc            55933  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.826  rustc            55935  55564    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n22.827  rustc            55936  55513    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n22.831  rustc            55935  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n22.832  rustc            55936  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n22.832  rustc            55953  55549    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n22.833  execsnoop        55954  55646    0 /usr/local/bin/execsnoop -t\n22.834  python3          55954  55646    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n22.842  docker           55971  55564    0 /usr/bin/docker --help\n22.843  docker           55972  55513    0 /usr/bin/docker --help\n22.855  docker           55991  55513    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n22.855  rustc            55953  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n22.856  docker           55992  55564    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n22.857  rustc            55998  55829    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n22.862  rustc            55998  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n22.867  runc             56022  1599     0 /usr/bin/runc --version\n22.868  runc             56023  1599     0 /usr/bin/runc --version\n22.869  rustc            56034  55792    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n22.870  docker-init      56035  1599     0 /usr/bin/docker-init --version\n22.870  docker-init      56036  1599     0 /usr/bin/docker-init --version\n22.871  docker           56039  55564    0 /usr/bin/docker info -f {{.SecurityOptions}}\n22.871  docker           56040  55549    0 /usr/bin/docker --help\n22.872  docker           56045  55513    0 /usr/bin/docker info -f {{.SecurityOptions}}\n22.876  docker           56066  55829    0 /usr/bin/docker --help\n22.876  rustc            56034  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n22.885  runc             56091  1599     0 /usr/bin/runc --version\n22.885  runc             56092  1599     0 /usr/bin/runc --version\n22.885  docker           56093  55549    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n22.888  docker           56110  55792    0 /usr/bin/docker --help\n22.888  docker-init      56109  1599     0 /usr/bin/docker-init --version\n22.891  docker           56111  55829    0 \n22.892  docker-init      56112  1599     0 /usr/bin/docker-init --version\n22.892  rustc            56120  55684    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n22.898  rustc            56120  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n22.901  runc             56144  1599     0 /usr/bin/runc --version\n22.903  runc             56150  1599     0 /usr/bin/runc --version\n22.904  docker           56155  55792    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n22.904  docker-init      56157  1599     0 /usr/bin/docker-init --version\n22.905  docker           56158  55549    0 /usr/bin/docker info -f {{.SecurityOptions}}\n22.906  docker-init      56159  1599     0 /usr/bin/docker-init --version\n22.907  docker           56174  55829    0 /usr/bin/docker info -f {{.SecurityOptions}}\n22.911  docker           56183  55684    0 /usr/bin/docker --help\n22.916  rustup           56204  55513    0 /home/xmoe/.cargo/bin/rustup toolchain list\n22.917  rustup           56205  55564    0 /home/xmoe/.cargo/bin/rustup toolchain list\n22.918  runc             56206  1599     0 /usr/bin/runc --version\n22.918  runc             56207  1599     0 /usr/bin/runc --version\n22.920  runc             56237  1599     0 /usr/bin/runc --version\n22.921  docker-init      56238  1599     0 /usr/bin/docker-init --version\n22.922  docker-init      56244  1599     0 /usr/bin/docker-init --version\n22.922  docker           56245  55792    0 /usr/bin/docker info -f {{.SecurityOptions}}\n22.923  rustup           56246  55513    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n22.923  rustup           56247  55564    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n22.924  docker-init      56248  1599     0 /usr/bin/docker-init --version\n22.926  docker           56254  55684    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n22.936  runc             56288  1599     0 /usr/bin/runc --version\n22.939  runc             56294  1599     0 /usr/bin/runc --version\n22.940  docker-init      56300  1599     0 /usr/bin/docker-init --version\n22.942  docker-init      56301  1599     0 /usr/bin/docker-init --version\n22.944  docker           56302  55684    0 /usr/bin/docker info -f {{.SecurityOptions}}\n22.948  rustup           56308  55829    0 /home/xmoe/.cargo/bin/rustup toolchain list\n22.949  rustup           56309  55513    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n22.952  rustup           56318  55549    0 /home/xmoe/.cargo/bin/rustup toolchain list\n22.955  rustup           56334  55564    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n22.957  runc             56342  1599     0 /usr/bin/runc --version\n22.960  rustup           56354  55829    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n22.960  docker-init      56355  1599     0 /usr/bin/docker-init --version\n22.965  rustup           56364  55792    0 /home/xmoe/.cargo/bin/rustup toolchain list\n22.971  rustup           56373  55792    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n22.977  uname            56382  55513    0 /usr/bin/uname -r\n22.982  uname            56383  55564    0 /usr/bin/uname -r\n22.985  rustup           56384  55549    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n22.987  rustup           56385  55829    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n22.991  rustup           56402  55684    0 /home/xmoe/.cargo/bin/rustup toolchain list\n22.997  rustup           56411  55792    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n22.998  docker           56413  55513    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n22.999  rustup           56412  55684    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.001  docker           56427  55564    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.012  rustup           56452  55549    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.016  uname            56461  55829    0 /usr/bin/uname -r\n23.025  runc             56462  49987    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b --log-format json --systemd-cgroup kill --all 8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b31584 9\n23.026  uname            56463  55792    0 /usr/bin/uname -r\n23.027  rustup           56469  55684    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.034  runc             56478  49987    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b --log-format json --systemd-cgroup delete 8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b31584\n23.041  docker           56484  55829    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.043  uname            56490  55549    0 /usr/bin/uname -r\n23.047  systemd-sysctl   56491  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb7e39a3 --prefix=/net/ipv4/neigh/vethb7e39a3 --prefix=/net/ipv6/conf/vethb7e39a3 --prefix=/net/ipv6/neigh/vethb7e39a3\n23.047  systemd-sysctl   56492  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth22901f8 --prefix=/net/ipv4/neigh/veth22901f8 --prefix=/net/ipv6/conf/veth22901f8 --prefix=/net/ipv6/neigh/veth22901f8\n23.049  docker           56494  55792    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.051  systemd-sysctl   56497  54510    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth17a9353 --prefix=/net/ipv4/neigh/veth17a9353 --prefix=/net/ipv6/conf/veth17a9353 --prefix=/net/ipv6/neigh/veth17a9353\n23.052  systemd-sysctl   56496  54522    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth48cca07 --prefix=/net/ipv4/neigh/veth48cca07 --prefix=/net/ipv6/conf/veth48cca07 --prefix=/net/ipv6/neigh/veth48cca07\n23.060  uname            56504  55684    0 /usr/bin/uname -r\n23.067  docker           56507  55549    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.068  containerd-shim  56508  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a978af6b start\n23.073  containerd-shim  56520  56508    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a978af6b -address /var/run/docker/containerd/containerd.sock\n23.077  runc             56530  56520    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a97 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a97 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a97 42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a978af6b\n23.083  exe              56541  56530    0 /proc/self/exe init\n23.084  docker           56543  55684    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.117  exe              56568  56530    0 /proc/1599/exe -exec-root=/var/run/docker 42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a978af6b d7da31e8f8e1\n23.137  exe              56576  1599     0 /proc/self/exe /var/run/docker/netns/952f96b918e5 all false\n23.162  runc             56589  48833    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/68355959d765aad8bf227fa53691f1da7c78466af4739606e5535912ada --log-format json --systemd-cgroup kill --all 68355959d765aad8bf227fa53691f1da7c78466af4739606e5535912ada85424 9\n23.168  runc             56596  48833    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/68355959d765aad8bf227fa53691f1da7c78466af4739606e5535912ada --log-format json --systemd-cgroup delete 68355959d765aad8bf227fa53691f1da7c78466af4739606e5535912ada85424\n23.169  containerd-shim  56599  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id fa2299019308ccdc0d053e4b83f0a87826a0d2c4c83ed0216afa2eb3c8314462 start\n23.171  systemd-sysctl   56606  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf8a38fd --prefix=/net/ipv4/neigh/vethf8a38fd --prefix=/net/ipv6/conf/vethf8a38fd --prefix=/net/ipv6/neigh/vethf8a38fd\n23.171  systemd-sysctl   56607  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth6fc7c7e --prefix=/net/ipv4/neigh/veth6fc7c7e --prefix=/net/ipv6/conf/veth6fc7c7e --prefix=/net/ipv6/neigh/veth6fc7c7e\n23.172  containerd-shim  56610  56599    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id fa2299019308ccdc0d053e4b83f0a87826a0d2c4c83ed0216afa2eb3c8314462 -address /var/run/docker/containerd/containerd.sock\n23.175  runc             56620  56610    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fa2299019308ccdc0d053e4b83f0a87826a0d2c4c83ed0216afa2eb3c83 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fa2299019308ccdc0d053e4b83f0a87826a0d2c4c83ed0216afa2eb3c83 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fa2299019308ccdc0d053e4b83f0a87826a0d2c4c83ed0216afa2eb3c83 fa2299019308ccdc0d053e4b83f0a87826a0d2c4c83ed0216afa2eb3c8314462\n23.178  runc             56626  56520    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a97 --log-format json --systemd-cgroup start 42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a978af6b\n23.183  exe              56635  56620    0 /proc/self/exe init\n23.185  sh               56561  56520    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n23.185  cargo            56636  56561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n23.196  cargo-native-tr  56636  56561    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n23.199  cargo            56637  56636    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n23.209  rustc            56645  56637    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.215  exe              56646  56620    0 /proc/1599/exe -exec-root=/var/run/docker fa2299019308ccdc0d053e4b83f0a87826a0d2c4c83ed0216afa2eb3c8314462 d7da31e8f8e1\n23.216  containerd-shim  56647  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b31584 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b delete\n23.219  runc             56660  56647    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b3158 --log-format json delete --force 8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b31584\n23.220  rustc            56661  56637    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n23.231  systemd-sysctl   56670  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth45545ef --prefix=/net/ipv4/neigh/veth45545ef --prefix=/net/ipv6/conf/veth45545ef --prefix=/net/ipv6/neigh/veth45545ef\n23.231  systemd-sysctl   56671  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth4312240 --prefix=/net/ipv4/neigh/veth4312240 --prefix=/net/ipv6/conf/veth4312240 --prefix=/net/ipv6/neigh/veth4312240\n23.236  exe              56673  1599     0 /proc/self/exe /var/run/docker/netns/c3ebc88a19aa all false\n23.255  execsnoop        56691  56636    0 /usr/local/bin/execsnoop -t\n23.255  python3          56691  56636    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n23.282  runc             56696  56610    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fa2299019308ccdc0d053e4b83f0a87826a0d2c4c83ed0216afa2eb3c83 --log-format json --systemd-cgroup start fa2299019308ccdc0d053e4b83f0a87826a0d2c4c83ed0216afa2eb3c8314462\n23.287  sh               56639  56610    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n23.288  cargo            56702  56639    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n23.298  cargo-native-tr  56702  56639    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n23.301  systemd-sysctl   56704  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha40893a --prefix=/net/ipv4/neigh/vetha40893a --prefix=/net/ipv6/conf/vetha40893a --prefix=/net/ipv6/neigh/vetha40893a\n23.301  systemd-sysctl   56703  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth60fc7e1 --prefix=/net/ipv4/neigh/veth60fc7e1 --prefix=/net/ipv6/conf/veth60fc7e1 --prefix=/net/ipv6/neigh/veth60fc7e1\n23.301  systemd-sysctl   56705  54510    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth84e20f5 --prefix=/net/ipv4/neigh/veth84e20f5 --prefix=/net/ipv6/conf/veth84e20f5 --prefix=/net/ipv6/neigh/veth84e20f5\n23.301  cargo            56706  56702    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n23.315  rustc            56707  56706    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.325  rustc            56709  56706    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n23.347  containerd-shim  56713  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id ce2f2e31920141e0611692e2e14efd73ae94254723b292c1b9729104af83a7e2 start\n23.350  containerd-shim  56720  56713    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id ce2f2e31920141e0611692e2e14efd73ae94254723b292c1b9729104af83a7e2 -address /var/run/docker/containerd/containerd.sock\n23.351  containerd-shim  56721  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 68355959d765aad8bf227fa53691f1da7c78466af4739606e5535912ada85424 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/68355959d765aad8bf227fa53691f1da7c78466af4739606e5535912ada delete\n23.353  runc             56736  56721    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/68355959d765aad8bf227fa53691f1da7c78466af4739606e5535912ada8542 --log-format json delete --force 68355959d765aad8bf227fa53691f1da7c78466af4739606e5535912ada85424\n23.354  runc             56737  56720    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ce2f2e31920141e0611692e2e14efd73ae94254723b292c1b9729104af8 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ce2f2e31920141e0611692e2e14efd73ae94254723b292c1b9729104af8 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ce2f2e31920141e0611692e2e14efd73ae94254723b292c1b9729104af8 ce2f2e31920141e0611692e2e14efd73ae94254723b292c1b9729104af83a7e2\n23.358  exe              56749  56737    0 /proc/self/exe init\n23.389  execsnoop        56758  56702    0 /usr/local/bin/execsnoop -t\n23.390  python3          56758  56702    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n23.391  exe              56761  56737    0 /proc/1599/exe -exec-root=/var/run/docker ce2f2e31920141e0611692e2e14efd73ae94254723b292c1b9729104af83a7e2 d7da31e8f8e1\n23.397  containerd-shim  56767  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 710f54f0e7966a1a1235ec45481be908847d35e1a959fb20faa0477f9e9cb902 start\n23.399  containerd-shim  56775  56767    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 710f54f0e7966a1a1235ec45481be908847d35e1a959fb20faa0477f9e9cb902 -address /var/run/docker/containerd/containerd.sock\n23.402  runc             56784  56775    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/710f54f0e7966a1a1235ec45481be908847d35e1a959fb20faa0477f9e9 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/710f54f0e7966a1a1235ec45481be908847d35e1a959fb20faa0477f9e9 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/710f54f0e7966a1a1235ec45481be908847d35e1a959fb20faa0477f9e9 710f54f0e7966a1a1235ec45481be908847d35e1a959fb20faa0477f9e9cb902\n23.407  exe              56791  56784    0 /proc/self/exe init\n23.411  exe              56794  1599     0 /proc/self/exe /var/run/docker/netns/f80d131f222c all false\n23.441  exe              56815  56784    0 /proc/1599/exe -exec-root=/var/run/docker 710f54f0e7966a1a1235ec45481be908847d35e1a959fb20faa0477f9e9cb902 d7da31e8f8e1\n23.464  exe              56822  1599     0 /proc/self/exe /var/run/docker/netns/b779c96be324 all false\n23.472  systemd-sysctl   56830  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth07c09c2 --prefix=/net/ipv4/neigh/veth07c09c2 --prefix=/net/ipv6/conf/veth07c09c2 --prefix=/net/ipv6/neigh/veth07c09c2\n23.496  runc             56841  56720    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ce2f2e31920141e0611692e2e14efd73ae94254723b292c1b9729104af8 --log-format json --systemd-cgroup start ce2f2e31920141e0611692e2e14efd73ae94254723b292c1b9729104af83a7e2\n23.501  sh               56752  56720    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n23.502  cargo            56847  56752    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n23.513  systemd-sysctl   56849  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth130827a --prefix=/net/ipv4/neigh/veth130827a --prefix=/net/ipv6/conf/veth130827a --prefix=/net/ipv6/neigh/veth130827a\n23.513  systemd-sysctl   56848  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth9e1ecf7 --prefix=/net/ipv4/neigh/veth9e1ecf7 --prefix=/net/ipv6/conf/veth9e1ecf7 --prefix=/net/ipv6/neigh/veth9e1ecf7\n23.514  cargo-native-tr  56847  56752    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n23.518  cargo            56850  56847    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n23.531  rustc            56851  56850    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.541  rustc            56853  56850    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n23.544  sh               56854  2147557   0 /bin/sh -c which ps\n23.545  which            56854  2147557   0 /usr/bin/which ps\n23.546  containerd-shim  56856  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id b96b8207cd81a2254bc1400c6e15807a463622df32a7150aaaa852eedbf2b6fa start\n23.547  runc             56858  56775    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/710f54f0e7966a1a1235ec45481be908847d35e1a959fb20faa0477f9e9 --log-format json --systemd-cgroup start 710f54f0e7966a1a1235ec45481be908847d35e1a959fb20faa0477f9e9cb902\n23.548  sh               56857  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n23.549  ps               56857  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n23.550  containerd-shim  56873  56856    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id b96b8207cd81a2254bc1400c6e15807a463622df32a7150aaaa852eedbf2b6fa -address /var/run/docker/containerd/containerd.sock\n23.553  sh               56808  56775    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n23.554  runc             56881  56873    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b96b8207cd81a2254bc1400c6e15807a463622df32a7150aaaa852eedbf --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b96b8207cd81a2254bc1400c6e15807a463622df32a7150aaaa852eedbf --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b96b8207cd81a2254bc1400c6e15807a463622df32a7150aaaa852eedbf b96b8207cd81a2254bc1400c6e15807a463622df32a7150aaaa852eedbf2b6fa\n23.554  cargo            56882  56808    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n23.560  exe              56889  56881    0 /proc/self/exe init\n23.567  cargo-native-tr  56882  56808    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n23.570  cargo            56892  56882    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n23.578  sh               56900  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n23.580  cpuUsage.sh      56900  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n23.581  sed              56901  56900    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n23.583  cat              56902  56900    0 /usr/bin/cat /proc/2240539/stat\n23.584  cat              56903  56900    0 /usr/bin/cat /proc/4193716/stat\n23.585  sleep            56904  56900    0 /usr/bin/sleep 1\n23.586  rustc            56905  56892    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.591  exe              56906  56881    0 /proc/1599/exe -exec-root=/var/run/docker b96b8207cd81a2254bc1400c6e15807a463622df32a7150aaaa852eedbf2b6fa d7da31e8f8e1\n23.596  rustc            56913  56892    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n23.616  execsnoop        56919  56847    0 /usr/local/bin/execsnoop -t\n23.616  python3          56919  56847    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n23.620  exe              56922  1599     0 /proc/self/exe /var/run/docker/netns/f8c58c9e3296 all false\n23.628  containerd-shim  56931  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9fd6e1207a55314adc77acbc5bf8d46c8cdc6d3aabaa60fc377a38b0626276c3 start\n23.631  containerd-shim  56938  56931    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 9fd6e1207a55314adc77acbc5bf8d46c8cdc6d3aabaa60fc377a38b0626276c3 -address /var/run/docker/containerd/containerd.sock\n23.634  execsnoop        56947  56882    0 /usr/local/bin/execsnoop -t\n23.634  python3          56947  56882    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n23.635  runc             56951  56938    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9fd6e1207a55314adc77acbc5bf8d46c8cdc6d3aabaa60fc377a38b0626 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9fd6e1207a55314adc77acbc5bf8d46c8cdc6d3aabaa60fc377a38b0626 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9fd6e1207a55314adc77acbc5bf8d46c8cdc6d3aabaa60fc377a38b0626 9fd6e1207a55314adc77acbc5bf8d46c8cdc6d3aabaa60fc377a38b0626276c3\n23.646  exe              56959  56951    0 /proc/self/exe init\n23.667  runc             56969  56873    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b96b8207cd81a2254bc1400c6e15807a463622df32a7150aaaa852eedbf --log-format json --systemd-cgroup start b96b8207cd81a2254bc1400c6e15807a463622df32a7150aaaa852eedbf2b6fa\n23.672  sh               56894  56873    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n23.673  cargo            56975  56894    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n23.676  exe              56976  56951    0 /proc/1599/exe -exec-root=/var/run/docker 9fd6e1207a55314adc77acbc5bf8d46c8cdc6d3aabaa60fc377a38b0626276c3 d7da31e8f8e1\n23.685  cargo-native-tr  56975  56894    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n23.688  cargo            56983  56975    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n23.699  rustc            56986  56983    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.703  exe              56987  1599     0 /proc/self/exe /var/run/docker/netns/1cadc37f4aa7 all false\n"
    },
    {
      "argv": [
        "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52250,
      "build_script_target_dir": "libc-c3c858474dcfa7e6",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build",
      "pid": 52250,
      "ppid": 51706,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52250,
      "build_script_target_dir": "libc-c3c858474dcfa7e6",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 52251,
      "ppid": 52250,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/ring-36133a68ed4b831a/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/ring-36133a68ed4b831a/build-script-build",
      "pid": 52530,
      "ppid": 51706,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-E",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/11703895368463712161detect_compiler_family.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52531,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-E",
        "-quiet",
        "-imultiarch",
        "aarch64-linux-gnu",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/11703895368463712161detect_compiler_family.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52532,
      "ppid": 52531,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52534,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52538,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/curve25519/curve25519.c",
        "-quiet",
        "-dumpbase",
        "curve25519.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/fad98b632b8ce3cc-curve25519.o",
        "-gdwarf-4",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52539,
      "ppid": 52538,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/fad98b632b8ce3cc-curve25519.o",
        "/tmp/cczdXGOR.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52561,
      "ppid": 52538,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52572,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/aes/aes_nohw.c",
        "-quiet",
        "-dumpbase",
        "aes_nohw.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca4b6ef5433f5aeb-aes_nohw.o",
        "-gdwarf-4",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52573,
      "ppid": 52572,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca4b6ef5433f5aeb-aes_nohw.o",
        "/tmp/cc68yptr.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52580,
      "ppid": 52572,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52583,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/bn/montgomery.c",
        "-quiet",
        "-dumpbase",
        "montgomery.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca8bd8684bb569fa-montgomery.o",
        "-gdwarf-4",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52585,
      "ppid": 52583,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca8bd8684bb569fa-montgomery.o",
        "/tmp/ccDXG3Ti.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52593,
      "ppid": 52583,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52603,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/bn/montgomery_inv.c",
        "-quiet",
        "-dumpbase",
        "montgomery_inv.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca8bd8684bb569fa-montgomery_inv.o",
        "-gdwarf-4",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52607,
      "ppid": 52603,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca8bd8684bb569fa-montgomery_inv.o",
        "/tmp/cc5yfwUN.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52616,
      "ppid": 52603,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52620,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/ec/ecp_nistz.c",
        "-quiet",
        "-dumpbase",
        "ecp_nistz.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-ecp_nistz.o",
        "-gdwarf-4",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52624,
      "ppid": 52620,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-ecp_nistz.o",
        "/tmp/ccTv4TO3.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52630,
      "ppid": 52620,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52632,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/ec/gfp_p256.c",
        "-quiet",
        "-dumpbase",
        "gfp_p256.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-gfp_p256.o",
        "-gdwarf-4",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52633,
      "ppid": 52632,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-gfp_p256.o",
        "/tmp/ccYu76h1.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52634,
      "ppid": 52632,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52637,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/ec/gfp_p384.c",
        "-quiet",
        "-dumpbase",
        "gfp_p384.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-gfp_p384.o",
        "-gdwarf-4",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52638,
      "ppid": 52637,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-gfp_p384.o",
        "/tmp/cciBg9dn.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52644,
      "ppid": 52637,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52646,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/ec/p256.c",
        "-quiet",
        "-dumpbase",
        "p256.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-p256.o",
        "-gdwarf-4",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52647,
      "ppid": 52646,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-p256.o",
        "/tmp/ccwGTM72.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52648,
      "ppid": 52646,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52653,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/limbs/limbs.c",
        "-quiet",
        "-dumpbase",
        "limbs.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a1949f2101df4b9c-limbs.o",
        "-gdwarf-4",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52654,
      "ppid": 52653,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a1949f2101df4b9c-limbs.o",
        "/tmp/ccA9Bm5z.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52658,
      "ppid": 52653,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52659,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/mem.c",
        "-quiet",
        "-dumpbase",
        "mem.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-mem.o",
        "-gdwarf-4",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52660,
      "ppid": 52659,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-mem.o",
        "/tmp/ccZb5VZZ.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52661,
      "ppid": 52659,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52662,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/poly1305/poly1305.c",
        "-quiet",
        "-dumpbase",
        "poly1305.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/bec76f70393ddef1-poly1305.o",
        "-gdwarf-4",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52663,
      "ppid": 52662,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/bec76f70393ddef1-poly1305.o",
        "/tmp/ccgsTPMd.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52664,
      "ppid": 52662,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52665,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/crypto.c",
        "-quiet",
        "-dumpbase",
        "crypto.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-crypto.o",
        "-gdwarf-4",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52666,
      "ppid": 52665,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-crypto.o",
        "/tmp/ccOHzoxr.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52667,
      "ppid": 52665,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52668,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/ec/p256-nistz.c",
        "-quiet",
        "-dumpbase",
        "p256-nistz.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-p256-nistz.o",
        "-gdwarf-4",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52669,
      "ppid": 52668,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-p256-nistz.o",
        "/tmp/ccCQGcRG.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52686,
      "ppid": 52668,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52687,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-E",
        "-lang-asm",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/aesv8-armx-linux64.S",
        "-mlittle-endian",
        "-mabi=lp64",
        "-std=c11",
        "-Wextra",
        "-Wall",
        "-Wbad-function-cast",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52688,
      "ppid": 52687,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "--gdwarf2",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-aesv8-armx-linux64.o",
        "/tmp/cc11RF9a.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52689,
      "ppid": 52687,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52690,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-E",
        "-lang-asm",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/ghashv8-armx-linux64.S",
        "-mlittle-endian",
        "-mabi=lp64",
        "-std=c11",
        "-Wextra",
        "-Wall",
        "-Wbad-function-cast",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52691,
      "ppid": 52690,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "--gdwarf2",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-ghashv8-armx-linux64.o",
        "/tmp/ccMQyQQn.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52692,
      "ppid": 52690,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52693,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-E",
        "-lang-asm",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/chacha-armv8-linux64.S",
        "-mlittle-endian",
        "-mabi=lp64",
        "-std=c11",
        "-Wextra",
        "-Wall",
        "-Wbad-function-cast",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52694,
      "ppid": 52693,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "--gdwarf2",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-chacha-armv8-linux64.o",
        "/tmp/ccQQKu1z.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52695,
      "ppid": 52693,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52696,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-E",
        "-lang-asm",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/chacha20_poly1305_armv8-linux64.S",
        "-mlittle-endian",
        "-mabi=lp64",
        "-std=c11",
        "-Wextra",
        "-Wall",
        "-Wbad-function-cast",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52697,
      "ppid": 52696,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "--gdwarf2",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-chacha20_poly1305_armv8-linux64.o",
        "/tmp/ccteYgTP.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52698,
      "ppid": 52696,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52699,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-E",
        "-lang-asm",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/vpaes-armv8-linux64.S",
        "-mlittle-endian",
        "-mabi=lp64",
        "-std=c11",
        "-Wextra",
        "-Wall",
        "-Wbad-function-cast",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52700,
      "ppid": 52699,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "--gdwarf2",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-vpaes-armv8-linux64.o",
        "/tmp/ccQag2N4.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52701,
      "ppid": 52699,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52702,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-E",
        "-lang-asm",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/armv8-mont-linux64.S",
        "-mlittle-endian",
        "-mabi=lp64",
        "-std=c11",
        "-Wextra",
        "-Wall",
        "-Wbad-function-cast",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52707,
      "ppid": 52702,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "--gdwarf2",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-armv8-mont-linux64.o",
        "/tmp/ccLRjINh.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52708,
      "ppid": 52702,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52713,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-E",
        "-lang-asm",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/p256-armv8-asm-linux64.S",
        "-mlittle-endian",
        "-mabi=lp64",
        "-std=c11",
        "-Wextra",
        "-Wall",
        "-Wbad-function-cast",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52714,
      "ppid": 52713,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "--gdwarf2",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-p256-armv8-asm-linux64.o",
        "/tmp/cckXcfa5.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52715,
      "ppid": 52713,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52716,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-E",
        "-lang-asm",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/ghash-neon-armv8-linux64.S",
        "-mlittle-endian",
        "-mabi=lp64",
        "-std=c11",
        "-Wextra",
        "-Wall",
        "-Wbad-function-cast",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52717,
      "ppid": 52716,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "--gdwarf2",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-ghash-neon-armv8-linux64.o",
        "/tmp/ccAnp4Mm.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52718,
      "ppid": 52716,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52719,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-E",
        "-lang-asm",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/aesv8-gcm-armv8-linux64.S",
        "-mlittle-endian",
        "-mabi=lp64",
        "-std=c11",
        "-Wextra",
        "-Wall",
        "-Wbad-function-cast",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52720,
      "ppid": 52719,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "--gdwarf2",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-aesv8-gcm-armv8-linux64.o",
        "/tmp/ccGEexmz.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52721,
      "ppid": 52719,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52722,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-E",
        "-lang-asm",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/sha512-armv8-linux64.S",
        "-mlittle-endian",
        "-mabi=lp64",
        "-std=c11",
        "-Wextra",
        "-Wall",
        "-Wbad-function-cast",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52723,
      "ppid": 52722,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "--gdwarf2",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-sha512-armv8-linux64.o",
        "/tmp/ccj7W6hN.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52724,
      "ppid": 52722,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52731,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-E",
        "-lang-asm",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/pregenerated/sha256-armv8-linux64.S",
        "-mlittle-endian",
        "-mabi=lp64",
        "-std=c11",
        "-Wextra",
        "-Wall",
        "-Wbad-function-cast",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52733,
      "ppid": 52731,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "--gdwarf2",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-sha256-armv8-linux64.o",
        "/tmp/ccPck4cr.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52741,
      "ppid": 52731,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "cq",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/libring_core_0_17_8_.a",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/fad98b632b8ce3cc-curve25519.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca4b6ef5433f5aeb-aes_nohw.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca8bd8684bb569fa-montgomery.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/ca8bd8684bb569fa-montgomery_inv.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-ecp_nistz.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-gfp_p256.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-gfp_p384.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-p256.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a1949f2101df4b9c-limbs.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-mem.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/bec76f70393ddef1-poly1305.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-crypto.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/a9af75d892b04b75-p256-nistz.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-aesv8-armx-linux64.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-ghashv8-armx-linux64.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-chacha-armv8-linux64.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/0431af03fd0c6b72-chacha20_poly1305_armv8-linux64.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 52743,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "s",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/libring_core_0_17_8_.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 52746,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-E",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/810360224297801178detect_compiler_family.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52750,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-E",
        "-quiet",
        "-imultiarch",
        "aarch64-linux-gnu",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/810360224297801178detect_compiler_family.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52754,
      "ppid": 52750,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52757,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "-Wcast-qual",
        "-Wconversion",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 52758,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/constant_time_test.c",
        "-quiet",
        "-dumpbase",
        "constant_time_test.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-constant_time_test.o",
        "-gdwarf-4",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 52761,
      "ppid": 52758,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-constant_time_test.o",
        "/tmp/ccNO11ax.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 52764,
      "ppid": 52758,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "cq",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/libring_core_0_17_8_test.a",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/7effb53edfc7fa2d-constant_time_test.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 52767,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "s",
        "/target/aarch64-unknown-linux-gnu/debug/build/ring-1b859b6c562a8e0d/out/libring_core_0_17_8_test.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52530,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 52768,
      "ppid": 52530,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52773,
      "build_script_target_dir": "rustls-2216ddcaf0bdcdf8",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build-script-build",
      "pid": 52773,
      "ppid": 51706,
      "root_cargo_pid": 51706,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "rustls",
      "cwd": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
      "event_id": "bsrun:357ca8740a0588d9:aa8e620880ea118c:01382d2620d23103",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
      "out_dir": "/target/debug/build/rustls-2216ddcaf0bdcdf8/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
      "success": true,
      "target": null,
      "version": "0.21.12",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-aarch64-0a7w79ep/src/rustls-0.21.12",
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
      "build_script_root_pid": 52250,
      "build_script_target_dir": "libc-c3c858474dcfa7e6",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 52251,
      "ppid": 52250,
      "root_cargo_pid": 51706,
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
