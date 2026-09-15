# `rustls` `0.21.12`

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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8",
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
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-51642-1783992784408712437.map",
  "pid": 51642,
  "ppid": 51485,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-51642-1783992784408712437.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
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
  "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "workspace_root": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12"
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
      "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
      "name": "rustls",
      "version": "0.21.12",
      "manifest_path": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12"
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
    "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "exit_code": 0,
  "kind": "exec",
  "pid": 51642,
  "ppid": 51485,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "event_id": "used:cc:1ba2bd07bed99e95:2b73a68bcc836751:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
  "pid": 51642,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "event_id": "used:cc:1ba2bd07bed99e95:eaee972e3c90e03b:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
  "pid": 51642,
  "sha256": "d19ded2f5e8e8ae2385f2dacbe55394770eebd501132fff1ee074e36c287f2d6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "event_id": "used:cc:1ba2bd07bed99e95:faa8bb92886ddc55:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
  "pid": 51642,
  "sha256": "f1adbcc51a207c0a2dc7d49e4d2564e9ca9f9b61a61bf506dfeccfc5e1b54e5b",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "event_id": "used:cc:1ba2bd07bed99e95:03e01daaa99638ee:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
  "pid": 51642,
  "sha256": "7f90a2084045b9134d6b1ff83ae1dda447bd93230d69d9c75afc1ba798711dd3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "event_id": "used:cc:1ba2bd07bed99e95:13341e70e14b61df:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
  "pid": 51642,
  "sha256": "b237ef03c4e46fc65a316e501ca519b8bbc300a16feb193d054be5030abf0b8d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "event_id": "used:cc:1ba2bd07bed99e95:931814120e1863c6:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
  "pid": 51642,
  "sha256": "b27303eaee92295bb7c14607f08d0446f6a3a152eff9838a27cace427b6bf078",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "event_id": "used:cc:1ba2bd07bed99e95:c32c2ecafe6de21b:23ed118ece042b34",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
  "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
  "pid": 51642,
  "sha256": "2a6cf24c0a0269e4833fdfcff9cd095c0e58be7a7e310e83ace955edb2ba5340",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "cargo_pkg_name": "rustls",
  "cargo_pkg_version": "0.21.12",
  "context_path": "/tmp/native-trace-49895-1783992779830/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-49895-1783992779830/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 51642,
  "ppid": 51485,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL",
    "/target/debug/build/rustls-2216ddcaf0bdcdf8",
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
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
      "kind": "object",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-51642-1783992784408712437.map",
  "pid": 51642,
  "ppid": 51485,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-51642-1783992784408712437.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/raw-dylibs",
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
  "pid": 51912,
  "ppid": 51484,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/raw-dylibs",
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
  "event_id": "used:cc:b47364ada97c6bc2:c167343c1cf57fcd:6abd7aadaee76ef4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
  "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
  "pid": 51912,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/raw-dylibs",
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
  "pid": 51912,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/raw-dylibs",
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
  "pid": 51912,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/raw-dylibs",
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
  "pid": 51912,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/raw-dylibs",
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
  "pid": 51912,
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/raw-dylibs",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
    "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/raw-dylibs",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/raw-dylibs",
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
  "context_path": "/tmp/native-trace-49895-1783992779830/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-49895-1783992779830/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 51912,
  "ppid": 51484,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
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
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/raw-dylibs",
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
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K",
    "/target/debug/build/libc-c3c858474dcfa7e6",
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
      "directory": "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K",
      "kind": "object",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
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
  "map_path": "/tmp/native-trace-link-cc-51912-1783992784698827144.map",
  "pid": 51912,
  "ppid": 51484,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-51912-1783992784698827144.map"
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/raw-dylibs",
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
  "pid": 52452,
  "ppid": 52385,
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/raw-dylibs",
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
  "event_id": "used:cc:d3ed579287892b7b:4ef2753d0f2ef543:0983853cb5c6903e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
  "path": "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
  "pid": 52452,
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/raw-dylibs",
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
  "pid": 52452,
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/raw-dylibs",
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
  "pid": 52452,
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/raw-dylibs",
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
  "pid": 52452,
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/raw-dylibs",
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
  "pid": 52452,
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/raw-dylibs",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
    "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/raw-dylibs",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/raw-dylibs",
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
  "context_path": "/tmp/native-trace-49895-1783992779830/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-49895-1783992779830/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 52452,
  "ppid": 52385,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
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
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/raw-dylibs",
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
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d",
    "/target/debug/build/ring-36133a68ed4b831a",
    "/target/debug/deps",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "/lib/x86_64-linux-gnu",
    "/lib64",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55670            55670        c    16         /target/debug/build/ring-36133a68ed4b831a",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55680            55680        c    16         /target/debug/build/ring-36133a68ed4b831a",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/59800            59800        c    16         /target/debug/build/ring-36133a68ed4b831a",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/636e0            636e0        9    16         /target/debug/build/ring-36133a68ed4b831a",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/636f0            636f0        9    16         /target/debug/build/ring-36133a68ed4b831a"
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
      "directory": "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d",
      "kind": "object",
      "path": "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
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
    },
    {
      "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55670            55670        c    16         /target/debug/build/ring-36133a68ed4b831a",
      "kind": "dynamic_library",
      "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55670            55670        c    16         /target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN102_$LT$core..iter..adapters..filter..Filter$LT$I$C$P$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h366b1fdc5249421eE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/build/ring-36133a68ed4b831a",
      "kind": "dynamic_library",
      "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN102_$LT$core..iter..adapters..filter..Filter$LT$I$C$P$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h366b1fdc5249421eE",
      "source": "link_map"
    },
    {
      "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55680            55680        c    16         /target/debug/build/ring-36133a68ed4b831a",
      "kind": "dynamic_library",
      "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55680            55680        c    16         /target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN102_$LT$core..iter..adapters..filter..Filter$LT$I$C$P$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17hdd043471a900c196E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/build/ring-36133a68ed4b831a",
      "kind": "dynamic_library",
      "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN102_$LT$core..iter..adapters..filter..Filter$LT$I$C$P$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17hdd043471a900c196E",
      "source": "link_map"
    },
    {
      "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/59800            59800        c    16         /target/debug/build/ring-36133a68ed4b831a",
      "kind": "dynamic_library",
      "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/59800            59800        c    16         /target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h522cca2806a5a384E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/build/ring-36133a68ed4b831a",
      "kind": "dynamic_library",
      "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h522cca2806a5a384E",
      "source": "link_map"
    },
    {
      "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/636e0            636e0        9    16         /target/debug/build/ring-36133a68ed4b831a",
      "kind": "dynamic_library",
      "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/636e0            636e0        9    16         /target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o:(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h3c3f8f1374e45b16E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/build/ring-36133a68ed4b831a",
      "kind": "dynamic_library",
      "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o:(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h3c3f8f1374e45b16E",
      "source": "link_map"
    },
    {
      "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/636f0            636f0        9    16         /target/debug/build/ring-36133a68ed4b831a",
      "kind": "dynamic_library",
      "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/636f0            636f0        9    16         /target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o:(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h5f762ba4a5828b0bE",
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
  "map_path": "/tmp/native-trace-link-cc-52452-1783992785890796029.map",
  "pid": 52452,
  "ppid": 52385,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-52452-1783992785890796029.map"
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
  "parsed_event_count": 878,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 880,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": ".runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9 --log-format json delete --force 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a\n17.500  rustup           54755  54542    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.524  rustup           54764  54542    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.525  systemd-sysctl   54765  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe425dec --prefix=/net/ipv4/neigh/vethe425dec --prefix=/net/ipv6/conf/vethe425dec --prefix=/net/ipv6/neigh/vethe425dec\n17.548  uname            54774  54542    0 /usr/bin/uname -r\n17.566  docker           54775  54542    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.602  systemd-sysctl   54789  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth76e10a3 --prefix=/net/ipv4/neigh/veth76e10a3 --prefix=/net/ipv6/conf/veth76e10a3 --prefix=/net/ipv6/neigh/veth76e10a3\n17.602  systemd-sysctl   54788  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf2069ec --prefix=/net/ipv4/neigh/vethf2069ec --prefix=/net/ipv6/conf/vethf2069ec --prefix=/net/ipv6/neigh/vethf2069ec\n17.617  containerd-shim  54791  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 start\n17.620  containerd-shim  54798  54791    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 -address /var/run/docker/containerd/containerd.sock\n17.624  runc             54808  54798    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10\n17.625  containerd-shim  54811  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f49 delete\n17.627  runc             54820  54811    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f495792 --log-format json delete --force a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922\n17.629  exe              54827  54808    0 /proc/self/exe init\n17.664  systemd-sysctl   54832  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7f2e47d --prefix=/net/ipv4/neigh/veth7f2e47d --prefix=/net/ipv6/conf/veth7f2e47d --prefix=/net/ipv6/neigh/veth7f2e47d\n17.679  exe              54838  54808    0 /proc/1599/exe -exec-root=/var/run/docker 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 d7da31e8f8e1\n17.699  exe              54846  1599     0 /proc/self/exe /var/run/docker/netns/3e401da5d4b2 all false\n17.758  runc             54864  54798    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --log-format json --systemd-cgroup start 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10\n17.764  sh               54831  54798    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.765  cargo            54870  54831    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n17.775  cargo-native-tr  54870  54831    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n17.778  cargo            54871  54870    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.788  rustc            54872  54871    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.800  rustc            54874  54871    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.809  runc             54878  49386    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b --log-format json --systemd-cgroup kill --all bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888 9\n17.826  runc             54885  49386    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b --log-format json --systemd-cgroup delete bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888\n17.838  execsnoop        54891  54870    0 /usr/local/bin/execsnoop -t\n17.839  python3          54891  54870    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.852  runc             54894  49353    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 --log-format json --systemd-cgroup kill --all a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7 9\n17.870  runc             54901  49353    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 --log-format json --systemd-cgroup delete a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7\n18.047  containerd-shim  54907  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b delete\n18.049  runc             54914  54907    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf788 --log-format json delete --force bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888\n18.086  systemd-sysctl   54919  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethfb8276c --prefix=/net/ipv4/neigh/vethfb8276c --prefix=/net/ipv6/conf/vethfb8276c --prefix=/net/ipv6/neigh/vethfb8276c\n18.094  containerd-shim  54921  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 delete\n18.096  runc             54928  54921    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f --log-format json delete --force a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7\n18.140  systemd-sysctl   54933  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth651aca6 --prefix=/net/ipv4/neigh/veth651aca6 --prefix=/net/ipv6/conf/veth651aca6 --prefix=/net/ipv6/neigh/veth651aca6\n18.206  runc             54934  49256    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 --log-format json --systemd-cgroup kill --all f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96 9\n18.223  runc             54940  49256    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 --log-format json --systemd-cgroup delete f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96\n18.403  containerd-shim  54946  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 delete\n18.406  runc             54953  54946    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da9 --log-format json delete --force f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96\n18.443  systemd-sysctl   54959  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd600a16 --prefix=/net/ipv4/neigh/vethd600a16 --prefix=/net/ipv6/conf/vethd600a16 --prefix=/net/ipv6/neigh/vethd600a16\n18.511  runc             54961  49929    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d --log-format json --systemd-cgroup kill --all 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637 9\n18.518  runc             54967  49929    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d --log-format json --systemd-cgroup delete 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637\n18.698  containerd-shim  54974  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d delete\n18.700  runc             54981  54974    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d9863 --log-format json delete --force 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637\n18.735  systemd-sysctl   54986  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5b8f709 --prefix=/net/ipv4/neigh/veth5b8f709 --prefix=/net/ipv6/conf/veth5b8f709 --prefix=/net/ipv6/neigh/veth5b8f709\n18.846  sh               54987  2147557   0 /bin/sh -c which ps\n18.847  which            54987  2147557   0 /usr/bin/which ps\n18.849  sh               54988  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.850  ps               54988  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.875  sh               54989  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n18.876  cpuUsage.sh      54989  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n18.877  sed              54990  54989    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.879  cat              54991  54989    0 /usr/bin/cat /proc/2240539/stat\n18.880  cat              54992  54989    0 /usr/bin/cat /proc/4193716/stat\n18.881  sleep            54993  54989    0 /usr/bin/sleep 1\n19.274  cargo            54994  54641    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n19.287  rustc            54995  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n19.316  rustc            55001  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n19.357  cc               55024  55001    0 /tmp/native-trace-54641-1783992801298/shims/cc -m64 /target/debug/build/valuable-0ca3a52e87f47781/rustcum31Fu/symbols.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2bcuvqydoknozqmp1me20ruil.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2hvolwvrh1z7h0esed9fdlkq6.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2ydqatcbwpyv0nfser2rvjw0s.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.320kk89i2c31bqlrt1pe5ftwu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.3dorb0xb6tyxiuzsrh06fg7wn.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.44p8ua3isbvp2so96dfqsrcv0.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.4mgnn3dy9r06fb4dhef909zhp.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54olwytbg728sxv8s6jzea9ac.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54xlj1thl6ekctt4ryak72mpk.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5gyye0zaqcjlw0qa72458hp4p.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5m686vmv93io6lluiiyhiylju.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.7d19io80brmbzee20rw5urjmi.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.b7inlg8jykc014dunu01jjkqu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.c3a0y0h3kjig5bmjwukot6pmm.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.deexadt1dri1ihovsh8z1lp29.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.dlbacscotl41na11230m8gkv8.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.e0jqet5ubfmmb5vnbm2c21wdk.15hdgiv.rcgu.o ...\n19.357  cc               55025  55024    0 /usr/bin/cc -m64 /target/debug/build/valuable-0ca3a52e87f47781/rustcum31Fu/symbols.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2bcuvqydoknozqmp1me20ruil.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2hvolwvrh1z7h0esed9fdlkq6.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2ydqatcbwpyv0nfser2rvjw0s.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.320kk89i2c31bqlrt1pe5ftwu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.3dorb0xb6tyxiuzsrh06fg7wn.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.44p8ua3isbvp2so96dfqsrcv0.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.4mgnn3dy9r06fb4dhef909zhp.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54olwytbg728sxv8s6jzea9ac.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54xlj1thl6ekctt4ryak72mpk.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5gyye0zaqcjlw0qa72458hp4p.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5m686vmv93io6lluiiyhiylju.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.7d19io80brmbzee20rw5urjmi.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.b7inlg8jykc014dunu01jjkqu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.c3a0y0h3kjig5bmjwukot6pmm.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.deexadt1dri1ihovsh8z1lp29.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.dlbacscotl41na11230m8gkv8.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.e0jqet5ubfmmb5vnbm2c21wdk.15hdgiv.rcgu.o ...\n19.360  collect2         55026  55025    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.361  ld.lld           55027  55026    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781 ...\n19.362  rust-lld         55027  55026    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.400  build-script-bu  55045  54994    0 /target/debug/build/valuable-0ca3a52e87f47781/build-script-build\n19.404  rustc            55047  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name valuable --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n19.684  cargo            55059  54870    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n19.697  rustc            55070  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n19.722  rustc            55113  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n19.722  rustc            55111  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.18/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=ba1b82e103e0280b ...\n19.821  cc               55188  55113    0 /tmp/native-trace-54870-1783992801742/shims/cc -m64 /target/debug/build/proc-macro2-46239aad0aaf2dde/rustcz8FJmv/symbols.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0bv3et31ep2k9sd4r4xv6yltt.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0edhhq7oafgl2yf0nrxumcg9r.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0g0902jm3uya6wioho7beok0j.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0owef7ksnbk6ukcc2242nefkr.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0rdzizyhqamtksvgo7enpq5az.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1r69zij4wcxunk2gd17a0kpg6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1sghvgwc08k4idxie37yo3pw0.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1wbfjtyvleo9dhvql6dw9ezks.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2om80ctxk1ydfs1240ujhhg0b.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2ylb2sbb9n609gy1nl3eivm1m.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.34jg2bcz8z6kfpvajxful9pig.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3dgkawms7tf7icnefiv8uh2ur.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3h5kxyomdhio13fti327b3ul4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3pfht32bkan9uc6xs96laffv6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3vy5vc4kvl4zobt41ffusuic4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3wfb4bv7o9ei3djc1ma3hgool.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.4sen9su2ywavj025286hzh4rs.0uq14k2.rcgu.o ...\n19.822  cc               55189  55188    0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-46239aad0aaf2dde/rustcz8FJmv/symbols.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0bv3et31ep2k9sd4r4xv6yltt.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0edhhq7oafgl2yf0nrxumcg9r.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0g0902jm3uya6wioho7beok0j.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0owef7ksnbk6ukcc2242nefkr.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0rdzizyhqamtksvgo7enpq5az.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1r69zij4wcxunk2gd17a0kpg6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1sghvgwc08k4idxie37yo3pw0.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1wbfjtyvleo9dhvql6dw9ezks.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2om80ctxk1ydfs1240ujhhg0b.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2ylb2sbb9n609gy1nl3eivm1m.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.34jg2bcz8z6kfpvajxful9pig.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3dgkawms7tf7icnefiv8uh2ur.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3h5kxyomdhio13fti327b3ul4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3pfht32bkan9uc6xs96laffv6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3vy5vc4kvl4zobt41ffusuic4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3wfb4bv7o9ei3djc1ma3hgool.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.4sen9su2ywavj025286hzh4rs.0uq14k2.rcgu.o ...\n19.826  collect2         55190  55189    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.827  ld.lld           55191  55190    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde ...\n19.828  rust-lld         55191  55190    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.883  sed              55209  54989    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n19.883  build-script-bu  55210  55059    0 /target/debug/build/proc-macro2-46239aad0aaf2dde/build-script-build\n19.885  cat              55211  54989    0 /usr/bin/cat /proc/2240539/stat\n19.885  rustc            55212  55210    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n19.886  cat              55214  54989    0 /usr/bin/cat /proc/4193716/stat\n19.895  rustc            55217  55210    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-1a2ad12dc9160ce7/out/probe build/probe.rs --target aarch64-unknown-linux-gnu\n19.922  rustc            55222  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n20.487  cross            55331  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.488  rustc            55334  55331    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.509  rustc            55334  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.521  rustc            55346  55331    0 /home/xmoe/.cargo/bin/rustc -vV\n20.542  rustc            55346  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.552  cargo            55356  55331    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.573  cargo            55356  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.584  rustc            55366  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.586  git              55365  2235138   0 /usr/bin/git config --get commit.template\n20.593  rustc            55368  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.601  git              55369  2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n20.604  rustc            55373  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.617  git              55374  2235138   0 /usr/bin/git status -z -uall\n20.629  rustc            55379  55331    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n20.632  git              55378  2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n20.651  rustc            55379  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n20.662  docker           55391  55331    0 /usr/bin/docker --help\n20.674  docker           55402  55331    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n20.686  runc             55412  1599     0 /usr/bin/runc --version\n20.689  docker-init      55418  1599     0 /usr/bin/docker-init --version\n20.690  docker           55419  55331    0 /usr/bin/docker info -f {{.SecurityOptions}}\n20.701  runc             55430  1599     0 /usr/bin/runc --version\n20.704  docker-init      55436  1599     0 /usr/bin/docker-init --version\n20.725  rustup           55440  55331    0 /home/xmoe/.cargo/bin/rustup toolchain list\n20.746  rustup           55449  55331    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n20.767  rustup           55458  55331    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n20.791  uname            55467  55331    0 /usr/bin/uname -r\n20.806  docker           55468  55331    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n20.842  systemd-sysctl   55483  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8170368 --prefix=/net/ipv4/neigh/veth8170368 --prefix=/net/ipv6/conf/veth8170368 --prefix=/net/ipv6/neigh/veth8170368\n20.842  systemd-sysctl   55482  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth81dd9a9 --prefix=/net/ipv4/neigh/veth81dd9a9 --prefix=/net/ipv6/conf/veth81dd9a9 --prefix=/net/ipv6/neigh/veth81dd9a9\n20.856  containerd-shim  55484  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 start\n20.859  containerd-shim  55491  55484    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 -address /var/run/docker/containerd/containerd.sock\n20.863  runc             55501  55491    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956\n20.867  exe              55509  55501    0 /proc/self/exe init\n20.885  cross            55513  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n20.887  rustc            55520  55513    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.891  rustc            55520  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.901  exe              55532  55501    0 /proc/1599/exe -exec-root=/var/run/docker 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 d7da31e8f8e1\n20.903  rustc            55539  55513    0 /home/xmoe/.cargo/bin/rustc -vV\n20.907  rustc            55539  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.913  cross            55549  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n20.914  rustc            55552  55549    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.917  cargo            55561  55513    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.918  cross            55564  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.919  rustc            55567  55564    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.920  exe              55576  1599     0 /proc/self/exe /var/run/docker/netns/8b628a44607d all false\n20.922  cargo            55561  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.924  rustc            55567  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.933  rustc            55596  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.936  rustc            55597  55564    0 /home/xmoe/.cargo/bin/rustc -vV\n20.940  rustc            55552  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.941  rustc            55597  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.942  rustc            55607  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.949  cargo            55614  55564    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.951  rustc            55616  55549    0 /home/xmoe/.cargo/bin/rustc -vV\n20.952  rustc            55625  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.954  cargo            55614  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.965  rustc            55637  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.967  runc             55639  55491    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --log-format json --systemd-cgroup start 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956\n20.972  sh               55511  55491    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n20.973  cargo            55646  55511    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n20.975  rustc            55647  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.977  rustc            55616  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.985  cargo-native-tr  55646  55511    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n20.986  cargo            55652  55549    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.987  rustc            55653  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.989  cargo            55654  55646    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n20.999  rustc            55666  55654    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.008  cargo            55652  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n21.011  rustc            55668  55654    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.019  rustc            55670  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.028  rustc            55674  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.040  rustc            55678  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.076  git              55683  2235138   0 /usr/bin/git worktree list --porcelain\n21.114  cross            55684  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n21.115  rustc            55687  55684    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.120  rustc            55687  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.131  runc             55701  47737    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a --log-format json --systemd-cgroup kill --all 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9 9\n21.131  rustc            55700  55684    0 /home/xmoe/.cargo/bin/rustc -vV\n21.136  rustc            55700  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.145  cargo            55716  55684    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.148  runc             55725  47737    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a --log-format json --systemd-cgroup delete 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9\n21.149  cargo            55716  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.160  rustc            55731  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.169  rustc            55733  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.192  rustc            55737  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.277  runc             55741  49799    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e --log-format json --systemd-cgroup kill --all f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e 9\n21.284  runc             55748  49799    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e --log-format json --systemd-cgroup delete f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e\n21.364  containerd-shim  55754  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a delete\n21.367  runc             55761  55754    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a --log-format json delete --force 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9\n21.369  runc             55767  50023    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc --log-format json --systemd-cgroup kill --all a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0 9\n21.386  runc             55773  50023    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc --log-format json --systemd-cgroup delete a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0\n21.408  systemd-sysctl   55779  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethae76c09 --prefix=/net/ipv4/neigh/vethae76c09 --prefix=/net/ipv6/conf/vethae76c09 --prefix=/net/ipv6/neigh/vethae76c09\n21.471  runc             55780  50289    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d67 --log-format json --systemd-cgroup kill --all 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb 9\n21.488  runc             55786  50289    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d67 --log-format json --systemd-cgroup delete 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb\n21.520  cross            55792  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n21.521  rustc            55795  55792    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.526  rustc            55795  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.537  rustc            55807  55792    0 /home/xmoe/.cargo/bin/rustc -vV\n21.542  rustc            55807  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.545  containerd-shim  55816  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e delete\n21.547  runc             55822  55816    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1 --log-format json delete --force f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e\n21.549  cross            55829  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n21.550  rustc            55832  55829    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.551  cargo            55833  55792    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.555  rustc            55832  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.555  cargo            55833  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.565  rustc            55853  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.567  rustc            55854  55829    0 /home/xmoe/.cargo/bin/rustc -vV\n21.572  rustc            55854  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.574  rustc            55864  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.581  cargo            55869  55829    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.583  systemd-sysctl   55870  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethddd6c57 --prefix=/net/ipv4/neigh/vethddd6c57 --prefix=/net/ipv6/conf/vethddd6c57 --prefix=/net/ipv6/neigh/vethddd6c57\n21.585  containerd-shim  55880  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc delete\n21.586  rustc            55884  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.586  cargo            55869  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.587  runc             55887  55880    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f --log-format json delete --force a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0\n21.596  rustc            55896  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.605  rustc            55898  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.617  rustc            55902  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.625  systemd-sysctl   55903  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf192d49 --prefix=/net/ipv4/neigh/vethf192d49 --prefix=/net/ipv6/conf/vethf192d49 --prefix=/net/ipv6/neigh/vethf192d49\n21.712  containerd-shim  55908  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d67 delete\n21.714  runc             55915  55908    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7c --log-format json delete --force 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb\n21.746  systemd-sysctl   55920  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7b4cddd --prefix=/net/ipv4/neigh/veth7b4cddd --prefix=/net/ipv6/conf/veth7b4cddd --prefix=/net/ipv6/neigh/veth7b4cddd\n22.883  rustc            55925  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.932  rustc            55927  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.959  rustc            55929  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.007  rustc            55931  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.058  rustc            55933  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.129  rustc            55935  55564    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.130  rustc            55936  55513    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.134  rustc            55935  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.134  rustc            55936  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.135  rustc            55953  55549    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.136  execsnoop        55954  55646    0 /usr/local/bin/execsnoop -t\n23.136  python3          55954  55646    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n23.145  docker           55971  55564    0 /usr/bin/docker --help\n23.145  docker           55972  55513    0 /usr/bin/docker --help\n23.157  docker           55991  55513    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.158  rustc            55953  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.158  docker           55992  55564    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.160  rustc            55998  55829    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.165  rustc            55998  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.170  runc             56022  1599     0 /usr/bin/runc --version\n23.170  runc             56023  1599     0 /usr/bin/runc --version\n23.172  rustc            56034  55792    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.173  docker-init      56035  1599     0 /usr/bin/docker-init --version\n23.173  docker-init      56036  1599     0 /usr/bin/docker-init --version\n23.174  docker           56039  55564    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.174  docker           56040  55549    0 /usr/bin/docker --help\n23.175  docker           56045  55513    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.179  docker           56066  55829    0 /usr/bin/docker --help\n23.179  rustc            56034  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.187  runc             56091  1599     0 /usr/bin/runc --version\n23.188  runc             56092  1599     0 /usr/bin/runc --version\n23.188  docker           56093  55549    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.191  docker           56110  55792    0 /usr/bin/docker --help\n23.191  docker-init      56109  1599     0 /usr/bin/docker-init --version\n23.193  docker           56111  55829    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.194  docker-init      56112  1599     0 /usr/bin/docker-init --version\n23.195  rustc            56120  55684    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.201  rustc            56120  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.204  runc             56144  1599     0 /usr/bin/runc --version\n23.205  runc             56150  1599     0 /usr/bin/runc --version\n23.207  docker           56155  55792    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.207  docker-init      56157  1599     0 /usr/bin/docker-init --version\n23.208  docker           56158  55549    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.208  docker-init      56159  1599     0 /usr/bin/docker-init --version\n23.210  docker           56174  55829    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.214  docker           56183  55684    0 /usr/bin/docker --help\n23.219  rustup           56204  55513    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.219  rustup           56205  55564    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.221  runc             56206  1599     0 /usr/bin/runc --version\n23.221  runc             56207  1599     0 /usr/bin/runc --version\n23.223  runc             56237  1599     0 /usr/bin/runc --version\n23.224  docker-init      56238  1599     0 /usr/bin/docker-init --version\n23.224  docker-init      56244  1599     0 /usr/bin/docker-init --version\n23.225  docker           56245  55792    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.226  rustup           56246  55513    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.226  rustup           56247  55564    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.226  docker-init      56248  1599     0 /usr/bin/docker-init --version\n23.228  docker           56254  55684    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.239  runc             56288  1599     0 /usr/bin/runc --version\n23.241  runc             56294  1599     0 /usr/bin/runc --version\n23.243  docker-init      56300  1599     0 /usr/bin/docker-init --version\n23.244  docker-init      56301  1599     0 /usr/bin/docker-init --version\n23.246  docker           56302  55684    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.251  rustup           56308  55829    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.252  rustup           56309  55513    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.255  rustup           56318  55549    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.257  rustup           56334  55564    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.260  runc             56342  1599     0 /usr/bin/runc --version\n23.262  rustup           56354  55829    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.263  docker-init      56355  1599     0 /usr/bin/docker-init --version\n23.268  rustup           56364  55792    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.274  rustup           56373  55792    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.279  uname            56382  55513    0 /usr/bin/uname -r\n23.285  uname            56383  55564    0 /usr/bin/uname -r\n23.288  rustup           56384  55549    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.290  rustup           56385  55829    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.294  rustup           56402  55684    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.300  rustup           56411  55792    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.301  docker           56413  55513    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.302  rustup           56412  55684    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.304  docker           56427  55564    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.314  rustup           56452  55549    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.319  uname            56461  55829    0 /usr/bin/uname -r\n23.328  runc             56462  49987    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b --log-format json --systemd-cgroup kill --all 8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b31584 9\n23.329  uname            56463  55792    0 /usr/bin/uname -r\n23.330  rustup           56469  55684    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.337  runc             56478  49987    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b --log-format json --systemd-cgroup delete 8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b31584\n23.343  docker           56484  55829    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.346  uname            56490  55549    0 /usr/bin/uname -r\n23.349  systemd-sysctl   56491  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb7e39a3 --prefix=/net/ipv4/neigh/vethb7e39a3 --prefix=/net/ipv6/conf/vethb7e39a3 --prefix=/net/ipv6/neigh/vethb7e39a3\n23.350  systemd-sysctl   56492  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth22901f8 --prefix=/net/ipv4/neigh/veth22901f8 --prefix=/net/ipv6/conf/veth22901f8 --prefix=/net/ipv6/neigh/veth22901f8\n23.352  docker           56494  55792    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.354  systemd-sysctl   56497  54510    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth17a9353 --prefix=/net/ipv4/neigh/veth17a9353 --prefix=/net/ipv6/conf/veth17a9353 --prefix=/net/ipv6/neigh/veth17a9353\n23.355  systemd-sysctl   56496  54522    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth48cca07 --prefix=/net/ipv4/neigh/veth48cca07 --prefix=/net/ipv6/conf/veth48cca07 --prefix=/net/ipv6/neigh/veth48cca07\n23.363  uname            56504  55684    0 /usr/bin/uname -r\n23.370  docker           56507  55549    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.371  containerd-shim  56508  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a978af6b start\n23.376  containerd-shim  56520  56508    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a978af6b -address /var/run/docker/containerd/containerd.sock\n23.379  runc             56530  56520    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a97 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a97 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a97 42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a978af6b\n23.386  exe              56541  56530    0 /proc/self/exe init\n23.387  docker           56543  55684    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.419  exe              56568  56530    0 /proc/1599/exe -exec-root=/var/run/docker 42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a978af6b d7da31e8f8e1\n23.439  exe              56576  1599     0 /proc/self/exe /var/run/docker/netns/952f96b918e5 all false\n"
}
```

#### Record 33

```json
{
  "argv": [],
  "build_script_related": true,
  "build_script_root_pid": 52088,
  "build_script_target_dir": "libc-c3c858474dcfa7e6",
  "comm": "rustc",
  "event": "process_exec",
  "image": "rustc",
  "pid": 52105,
  "ppid": 52088,
  "root_cargo_pid": 51426,
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

#### Record 34

```json
{
  "argv": [
    "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52088,
  "build_script_target_dir": "libc-c3c858474dcfa7e6",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build",
  "pid": 52088,
  "ppid": 51426,
  "root_cargo_pid": 51426,
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

#### Record 35

```json
{
  "argv": [
    "/target/debug/build/ring-36133a68ed4b831a/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/ring-36133a68ed4b831a/build-script-build",
  "pid": 52478,
  "ppid": 51426,
  "root_cargo_pid": 51426,
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
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-E",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/13880850535424185224detect_compiler_family.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 52479,
  "ppid": 52478,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-E",
    "-quiet",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/13880850535424185224detect_compiler_family.c",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-dumpbase",
    "13880850535424185224detect_compiler_family.c",
    "-dumpbase-ext",
    ".c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 52480,
  "ppid": 52479,
  "root_cargo_pid": 51426,
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
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 52482,
  "ppid": 52478,
  "root_cargo_pid": 51426,
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
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 52483,
  "ppid": 52478,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/curve25519/curve25519.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "fad98b632b8ce3cc-curve25519.c",
    "-dumpbase-ext",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 52484,
  "ppid": 52483,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/fad98b632b8ce3cc-curve25519.o",
    "/tmp/ccvqDvzH.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 52500,
  "ppid": 52483,
  "root_cargo_pid": 51426,
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
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 52522,
  "ppid": 52478,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/aes/aes_nohw.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "ca4b6ef5433f5aeb-aes_nohw.c",
    "-dumpbase-ext",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 52523,
  "ppid": 52522,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/ca4b6ef5433f5aeb-aes_nohw.o",
    "/tmp/ccdmfLIU.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 52527,
  "ppid": 52522,
  "root_cargo_pid": 51426,
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
  "argv": [],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "cc1",
  "pid": 52537,
  "ppid": 52535,
  "root_cargo_pid": 51426,
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

#### Record 46

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 52535,
  "ppid": 52478,
  "root_cargo_pid": 51426,
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

#### Record 47

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/ca8bd8684bb569fa-montgomery.o",
    "/tmp/cctFwzKT.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 52540,
  "ppid": 52535,
  "root_cargo_pid": 51426,
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
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 52541,
  "ppid": 52478,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/bn/montgomery_inv.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "ca8bd8684bb569fa-montgomery_inv.c",
    "-dumpbase-ext",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 52542,
  "ppid": 52541,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/ca8bd8684bb569fa-montgomery_inv.o",
    "/tmp/ccgr0S76.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 52544,
  "ppid": 52541,
  "root_cargo_pid": 51426,
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
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 52545,
  "ppid": 52478,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/ecp_nistz.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "a9af75d892b04b75-ecp_nistz.c",
    "-dumpbase-ext",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 52547,
  "ppid": 52545,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-ecp_nistz.o",
    "/tmp/cc0oG8eG.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 52549,
  "ppid": 52545,
  "root_cargo_pid": 51426,
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
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 52550,
  "ppid": 52478,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/gfp_p256.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "a9af75d892b04b75-gfp_p256.c",
    "-dumpbase-ext",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 52551,
  "ppid": 52550,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-gfp_p256.o",
    "/tmp/ccDvElmp.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 52552,
  "ppid": 52550,
  "root_cargo_pid": 51426,
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
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 52553,
  "ppid": 52478,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/gfp_p384.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "a9af75d892b04b75-gfp_p384.c",
    "-dumpbase-ext",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 52554,
  "ppid": 52553,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-gfp_p384.o",
    "/tmp/ccpLQk4K.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 52560,
  "ppid": 52553,
  "root_cargo_pid": 51426,
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
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 52562,
  "ppid": 52478,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/p256.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "a9af75d892b04b75-p256.c",
    "-dumpbase-ext",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 52564,
  "ppid": 52562,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-p256.o",
    "/tmp/ccmwAhtu.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 52576,
  "ppid": 52562,
  "root_cargo_pid": 51426,
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
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 52578,
  "ppid": 52478,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/limbs/limbs.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "a1949f2101df4b9c-limbs.c",
    "-dumpbase-ext",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 52579,
  "ppid": 52578,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a1949f2101df4b9c-limbs.o",
    "/tmp/cc8E5cjT.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 52584,
  "ppid": 52578,
  "root_cargo_pid": 51426,
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
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 52587,
  "ppid": 52478,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/mem.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "7effb53edfc7fa2d-mem.c",
    "-dumpbase-ext",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 52590,
  "ppid": 52587,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/7effb53edfc7fa2d-mem.o",
    "/tmp/cc5vAgys.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 52595,
  "ppid": 52587,
  "root_cargo_pid": 51426,
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
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 52602,
  "ppid": 52478,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/poly1305/poly1305.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "bec76f70393ddef1-poly1305.c",
    "-dumpbase-ext",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 52606,
  "ppid": 52602,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/bec76f70393ddef1-poly1305.o",
    "/tmp/ccIZ14KA.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 52618,
  "ppid": 52602,
  "root_cargo_pid": 51426,
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
    "/usr/bin/riscv64-linux-gnu-ar",
    "cq",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/libring_core_0_17_8_.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/fad98b632b8ce3cc-curve25519.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/ca4b6ef5433f5aeb-aes_nohw.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/ca8bd8684bb569fa-montgomery.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/ca8bd8684bb569fa-montgomery_inv.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-ecp_nistz.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-gfp_p256.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-gfp_p384.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-p256.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a1949f2101df4b9c-limbs.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/7effb53edfc7fa2d-mem.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/bec76f70393ddef1-poly1305.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-ar",
  "pid": 52626,
  "ppid": 52478,
  "root_cargo_pid": 51426,
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
    "/usr/bin/riscv64-linux-gnu-ar",
    "s",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/libring_core_0_17_8_.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-ar",
  "pid": 52631,
  "ppid": 52478,
  "root_cargo_pid": 51426,
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
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-E",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/16141142337147692699detect_compiler_family.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 52635,
  "ppid": 52478,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-E",
    "-quiet",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/16141142337147692699detect_compiler_family.c",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-dumpbase",
    "16141142337147692699detect_compiler_family.c",
    "-dumpbase-ext",
    ".c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 52636,
  "ppid": 52635,
  "root_cargo_pid": 51426,
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
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 52639,
  "ppid": 52478,
  "root_cargo_pid": 51426,
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
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-Wall",
    "-Wextra",
    "-fvisibility=hidden",
    "-std=c1x",
    "-Wall",
    "-Wbad-function-cast",
    "-Wcast-align",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 52640,
  "ppid": 52478,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/constant_time_test.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "7effb53edfc7fa2d-constant_time_test.c",
    "-dumpbase-ext",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 52641,
  "ppid": 52640,
  "root_cargo_pid": 51426,
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
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/7effb53edfc7fa2d-constant_time_test.o",
    "/tmp/ccbaU115.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 52642,
  "ppid": 52640,
  "root_cargo_pid": 51426,
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
    "/usr/bin/riscv64-linux-gnu-ar",
    "cq",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/libring_core_0_17_8_test.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/7effb53edfc7fa2d-constant_time_test.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-ar",
  "pid": 52643,
  "ppid": 52478,
  "root_cargo_pid": 51426,
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
    "/usr/bin/riscv64-linux-gnu-ar",
    "s",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/libring_core_0_17_8_test.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52478,
  "build_script_target_dir": "ring-36133a68ed4b831a",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-ar",
  "pid": 52645,
  "ppid": 52478,
  "root_cargo_pid": 51426,
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
  "build_script_root_pid": 52652,
  "build_script_target_dir": "rustls-2216ddcaf0bdcdf8",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build-script-build",
  "pid": 52652,
  "ppid": 51426,
  "root_cargo_pid": 51426,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "_build_script_out_dir": "/target/debug/build/rustls-2216ddcaf0bdcdf8/out"
}
```

#### Record 83

```json
{
  "crate": "rustls",
  "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "event_id": "bsrun:2aaa3dada998f4ea:aa8e620880ea118c:01382d2620d23103",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
  "out_dir": "/target/debug/build/rustls-2216ddcaf0bdcdf8/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
  "success": true,
  "target": null,
  "version": "0.21.12",
  "_owner": {
    "crate": "rustls",
    "version": "0.21.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
    "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
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
  "argv": [],
  "build_script_related": true,
  "build_script_root_pid": 52088,
  "build_script_target_dir": "libc-c3c858474dcfa7e6",
  "comm": "rustc",
  "event": "process_exec",
  "image": "rustc",
  "pid": 52105,
  "ppid": 52088,
  "root_cargo_pid": 51426,
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
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/curve25519/curve25519.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "fad98b632b8ce3cc-curve25519.c",
    "-dumpbase-ext",
    "..."
  ],
  "src": "crypto/curve25519/curve25519.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/fad98b632b8ce3cc-curve25519.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52484,
  "ppid": 52483,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51426,
  "build_script_root_pid": 52478,
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
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/aes/aes_nohw.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "ca4b6ef5433f5aeb-aes_nohw.c",
    "-dumpbase-ext",
    "..."
  ],
  "src": "crypto/fipsmodule/aes/aes_nohw.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/ca4b6ef5433f5aeb-aes_nohw.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52523,
  "ppid": 52522,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51426,
  "build_script_root_pid": 52478,
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
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/bn/montgomery_inv.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "ca8bd8684bb569fa-montgomery_inv.c",
    "-dumpbase-ext",
    "..."
  ],
  "src": "crypto/fipsmodule/bn/montgomery_inv.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/ca8bd8684bb569fa-montgomery_inv.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52542,
  "ppid": 52541,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51426,
  "build_script_root_pid": 52478,
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
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/ecp_nistz.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "a9af75d892b04b75-ecp_nistz.c",
    "-dumpbase-ext",
    "..."
  ],
  "src": "crypto/fipsmodule/ec/ecp_nistz.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-ecp_nistz.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52547,
  "ppid": 52545,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51426,
  "build_script_root_pid": 52478,
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
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/gfp_p256.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "a9af75d892b04b75-gfp_p256.c",
    "-dumpbase-ext",
    "..."
  ],
  "src": "crypto/fipsmodule/ec/gfp_p256.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-gfp_p256.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52551,
  "ppid": 52550,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51426,
  "build_script_root_pid": 52478,
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
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/gfp_p384.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "a9af75d892b04b75-gfp_p384.c",
    "-dumpbase-ext",
    "..."
  ],
  "src": "crypto/fipsmodule/ec/gfp_p384.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-gfp_p384.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52554,
  "ppid": 52553,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51426,
  "build_script_root_pid": 52478,
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
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/fipsmodule/ec/p256.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "a9af75d892b04b75-p256.c",
    "-dumpbase-ext",
    "..."
  ],
  "src": "crypto/fipsmodule/ec/p256.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-p256.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52564,
  "ppid": 52562,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51426,
  "build_script_root_pid": 52478,
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
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/limbs/limbs.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "a1949f2101df4b9c-limbs.c",
    "-dumpbase-ext",
    "..."
  ],
  "src": "crypto/limbs/limbs.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a1949f2101df4b9c-limbs.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52579,
  "ppid": 52578,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51426,
  "build_script_root_pid": 52478,
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
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/mem.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "7effb53edfc7fa2d-mem.c",
    "-dumpbase-ext",
    "..."
  ],
  "src": "crypto/mem.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/7effb53edfc7fa2d-mem.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52590,
  "ppid": 52587,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51426,
  "build_script_root_pid": 52478,
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
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/poly1305/poly1305.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "bec76f70393ddef1-poly1305.c",
    "-dumpbase-ext",
    "..."
  ],
  "src": "crypto/poly1305/poly1305.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/bec76f70393ddef1-poly1305.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52606,
  "ppid": 52602,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51426,
  "build_script_root_pid": 52478,
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
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "include",
    "-I",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-dD",
    "-D",
    "NDEBUG",
    "crypto/constant_time_test.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
    "-dumpbase",
    "7effb53edfc7fa2d-constant_time_test.c",
    "-dumpbase-ext",
    "..."
  ],
  "src": "crypto/constant_time_test.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/7effb53edfc7fa2d-constant_time_test.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 52641,
  "ppid": 52640,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51426,
  "build_script_root_pid": 52478,
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
  "event": "archive",
  "tool": "/usr/bin/riscv64-linux-gnu-ar",
  "real_tool": "/usr/bin/riscv64-linux-gnu-ar",
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "cq",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/libring_core_0_17_8_.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/fad98b632b8ce3cc-curve25519.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/ca4b6ef5433f5aeb-aes_nohw.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/ca8bd8684bb569fa-montgomery.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/ca8bd8684bb569fa-montgomery_inv.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-ecp_nistz.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-gfp_p256.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-gfp_p384.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-p256.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a1949f2101df4b9c-limbs.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/7effb53edfc7fa2d-mem.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/bec76f70393ddef1-poly1305.o"
  ],
  "archive": "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/libring_core_0_17_8_.a",
  "objects": [
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/fad98b632b8ce3cc-curve25519.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/ca4b6ef5433f5aeb-aes_nohw.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/ca8bd8684bb569fa-montgomery.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/ca8bd8684bb569fa-montgomery_inv.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-ecp_nistz.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-gfp_p256.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-gfp_p384.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-p256.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a1949f2101df4b9c-limbs.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/7effb53edfc7fa2d-mem.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/bec76f70393ddef1-poly1305.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 52626,
  "ppid": 52478,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51426,
  "build_script_root_pid": 52478,
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

#### Record 99

```json
{
  "event": "archive",
  "tool": "/usr/bin/riscv64-linux-gnu-ar",
  "real_tool": "/usr/bin/riscv64-linux-gnu-ar",
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "cq",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/libring_core_0_17_8_test.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/7effb53edfc7fa2d-constant_time_test.o"
  ],
  "archive": "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/libring_core_0_17_8_test.a",
  "objects": [
    "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/7effb53edfc7fa2d-constant_time_test.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 52643,
  "ppid": 52478,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
  "root_cargo_pid": 51426,
  "build_script_root_pid": 52478,
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
  "time": "2026-07-14T01:33:27.856272+00:00",
  "crate": "rustls",
  "version": "0.21.12",
  "architecture": "riscv64",
  "duration_seconds": 32.67041838588193,
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
        "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
        "manifest_path": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12/Cargo.toml"
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
      "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
      "workspace_root": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12"
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
          "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
          "name": "rustls",
          "version": "0.21.12",
          "manifest_path": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12"
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
        "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
      "exit_code": 0,
      "kind": "exec",
      "pid": 51642,
      "ppid": 51485,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
      "event_id": "used:cc:1ba2bd07bed99e95:2b73a68bcc836751:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
      "pid": 51642,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
      "event_id": "used:cc:1ba2bd07bed99e95:eaee972e3c90e03b:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
      "pid": 51642,
      "sha256": "d19ded2f5e8e8ae2385f2dacbe55394770eebd501132fff1ee074e36c287f2d6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
      "event_id": "used:cc:1ba2bd07bed99e95:faa8bb92886ddc55:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
      "pid": 51642,
      "sha256": "f1adbcc51a207c0a2dc7d49e4d2564e9ca9f9b61a61bf506dfeccfc5e1b54e5b",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
      "event_id": "used:cc:1ba2bd07bed99e95:03e01daaa99638ee:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
      "pid": 51642,
      "sha256": "7f90a2084045b9134d6b1ff83ae1dda447bd93230d69d9c75afc1ba798711dd3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
      "event_id": "used:cc:1ba2bd07bed99e95:13341e70e14b61df:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
      "pid": 51642,
      "sha256": "b237ef03c4e46fc65a316e501ca519b8bbc300a16feb193d054be5030abf0b8d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
      "event_id": "used:cc:1ba2bd07bed99e95:931814120e1863c6:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
      "pid": 51642,
      "sha256": "b27303eaee92295bb7c14607f08d0446f6a3a152eff9838a27cace427b6bf078",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
      "event_id": "used:cc:1ba2bd07bed99e95:c32c2ecafe6de21b:23ed118ece042b34",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8",
      "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
      "pid": 51642,
      "sha256": "2a6cf24c0a0269e4833fdfcff9cd095c0e58be7a7e310e83ace955edb2ba5340",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
      "cargo_pkg_name": "rustls",
      "cargo_pkg_version": "0.21.12",
      "context_path": "/tmp/native-trace-49895-1783992779830/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-49895-1783992779830/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 51642,
      "ppid": 51485,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL",
        "/target/debug/build/rustls-2216ddcaf0bdcdf8",
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
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/rustcQI8sYL/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0v40u82a7xtsohqf2va0cn52n.0jcs28n.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.4220vpav03iv0tr7630e8dtrr.0jcs28n.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.6l92xtenga6bv2s23h9984sce.0jcs28n.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.8c4w61f1lnlrfwfkbkbqnere2.0jcs28n.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.djtjq80kcradebrmwoxpvb675.0jcs28n.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustls-2216ddcaf0bdcdf8",
          "kind": "object",
          "path": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build_script_build-2216ddcaf0bdcdf8.0zr0f4j1xe9xqanb7ji0ltxiv.0jcs28n.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-51642-1783992784408712437.map",
      "pid": 51642,
      "ppid": 51485,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-51642-1783992784408712437.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/raw-dylibs",
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
      "pid": 51912,
      "ppid": 51484,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/raw-dylibs",
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
      "event_id": "used:cc:b47364ada97c6bc2:c167343c1cf57fcd:6abd7aadaee76ef4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6",
      "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
      "pid": 51912,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/raw-dylibs",
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
      "pid": 51912,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/raw-dylibs",
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
      "pid": 51912,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/raw-dylibs",
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
      "pid": 51912,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/raw-dylibs",
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
      "pid": 51912,
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/raw-dylibs",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.0.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.1.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.build_script_build.bbd1cacccd498544-cgu.2.rcgu.o",
        "/target/debug/build/libc-c3c858474dcfa7e6/build_script_build-c3c858474dcfa7e6.ds6xn713rx12rkfv0y4pqv6nh.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/raw-dylibs",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/raw-dylibs",
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
      "context_path": "/tmp/native-trace-49895-1783992779830/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-49895-1783992779830/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 51912,
      "ppid": 51484,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
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
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/raw-dylibs",
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
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K",
        "/target/debug/build/libc-c3c858474dcfa7e6",
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
          "directory": "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K",
          "kind": "object",
          "path": "/target/debug/build/libc-c3c858474dcfa7e6/rustcAZlT1K/symbols.o",
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
      "map_path": "/tmp/native-trace-link-cc-51912-1783992784698827144.map",
      "pid": 51912,
      "ppid": 51484,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-51912-1783992784698827144.map"
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/raw-dylibs",
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
      "pid": 52452,
      "ppid": 52385,
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/raw-dylibs",
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
      "event_id": "used:cc:d3ed579287892b7b:4ef2753d0f2ef543:0983853cb5c6903e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a",
      "path": "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
      "pid": 52452,
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/raw-dylibs",
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
      "pid": 52452,
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/raw-dylibs",
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
      "pid": 52452,
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/raw-dylibs",
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
      "pid": 52452,
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/raw-dylibs",
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
      "pid": 52452,
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/raw-dylibs",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.0.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o",
        "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.1uzih3ezcyenzrgel4t9kzru6.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/raw-dylibs",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/raw-dylibs",
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
      "context_path": "/tmp/native-trace-49895-1783992779830/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-49895-1783992779830/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 52452,
      "ppid": 52385,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
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
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/raw-dylibs",
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
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d",
        "/target/debug/build/ring-36133a68ed4b831a",
        "/target/debug/deps",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "/lib/x86_64-linux-gnu",
        "/lib64",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55670            55670        c    16         /target/debug/build/ring-36133a68ed4b831a",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55680            55680        c    16         /target/debug/build/ring-36133a68ed4b831a",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/59800            59800        c    16         /target/debug/build/ring-36133a68ed4b831a",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/636e0            636e0        9    16         /target/debug/build/ring-36133a68ed4b831a",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/636f0            636f0        9    16         /target/debug/build/ring-36133a68ed4b831a"
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
          "directory": "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d",
          "kind": "object",
          "path": "/target/debug/build/ring-36133a68ed4b831a/rustcIgHU5d/symbols.o",
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
        },
        {
          "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55670            55670        c    16         /target/debug/build/ring-36133a68ed4b831a",
          "kind": "dynamic_library",
          "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55670            55670        c    16         /target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN102_$LT$core..iter..adapters..filter..Filter$LT$I$C$P$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h366b1fdc5249421eE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/build/ring-36133a68ed4b831a",
          "kind": "dynamic_library",
          "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN102_$LT$core..iter..adapters..filter..Filter$LT$I$C$P$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h366b1fdc5249421eE",
          "source": "link_map"
        },
        {
          "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55680            55680        c    16         /target/debug/build/ring-36133a68ed4b831a",
          "kind": "dynamic_library",
          "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/55680            55680        c    16         /target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN102_$LT$core..iter..adapters..filter..Filter$LT$I$C$P$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17hdd043471a900c196E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/build/ring-36133a68ed4b831a",
          "kind": "dynamic_library",
          "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN102_$LT$core..iter..adapters..filter..Filter$LT$I$C$P$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17hdd043471a900c196E",
          "source": "link_map"
        },
        {
          "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/59800            59800        c    16         /target/debug/build/ring-36133a68ed4b831a",
          "kind": "dynamic_library",
          "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/59800            59800        c    16         /target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h522cca2806a5a384E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/build/ring-36133a68ed4b831a",
          "kind": "dynamic_library",
          "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.1.rcgu.o:(.text._ZN96_$LT$core..iter..adapters..map..Map$LT$I$C$F$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h522cca2806a5a384E",
          "source": "link_map"
        },
        {
          "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/636e0            636e0        9    16         /target/debug/build/ring-36133a68ed4b831a",
          "kind": "dynamic_library",
          "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/636e0            636e0        9    16         /target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o:(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h3c3f8f1374e45b16E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/build/ring-36133a68ed4b831a",
          "kind": "dynamic_library",
          "path": "/target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o:(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h3c3f8f1374e45b16E",
          "source": "link_map"
        },
        {
          "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/636f0            636f0        9    16         /target/debug/build/ring-36133a68ed4b831a",
          "kind": "dynamic_library",
          "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ring-0.17.8/636f0            636f0        9    16         /target/debug/build/ring-36133a68ed4b831a/build_script_build-36133a68ed4b831a.build_script_build.ac43f695900d9498-cgu.2.rcgu.o:(.text._ZN97_$LT$alloc..vec..into_iter..IntoIter$LT$T$C$A$GT$$u20$as$u20$core..iter..adapters..SourceIter$GT$8as_inner17h5f762ba4a5828b0bE",
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
      "map_path": "/tmp/native-trace-link-cc-52452-1783992785890796029.map",
      "pid": 52452,
      "ppid": 52385,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-52452-1783992785890796029.map"
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
      "parsed_event_count": 878,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 880,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": ".runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9 --log-format json delete --force 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a\n17.500  rustup           54755  54542    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.524  rustup           54764  54542    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.525  systemd-sysctl   54765  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe425dec --prefix=/net/ipv4/neigh/vethe425dec --prefix=/net/ipv6/conf/vethe425dec --prefix=/net/ipv6/neigh/vethe425dec\n17.548  uname            54774  54542    0 /usr/bin/uname -r\n17.566  docker           54775  54542    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.602  systemd-sysctl   54789  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth76e10a3 --prefix=/net/ipv4/neigh/veth76e10a3 --prefix=/net/ipv6/conf/veth76e10a3 --prefix=/net/ipv6/neigh/veth76e10a3\n17.602  systemd-sysctl   54788  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf2069ec --prefix=/net/ipv4/neigh/vethf2069ec --prefix=/net/ipv6/conf/vethf2069ec --prefix=/net/ipv6/neigh/vethf2069ec\n17.617  containerd-shim  54791  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 start\n17.620  containerd-shim  54798  54791    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 -address /var/run/docker/containerd/containerd.sock\n17.624  runc             54808  54798    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10\n17.625  containerd-shim  54811  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f49 delete\n17.627  runc             54820  54811    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f495792 --log-format json delete --force a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922\n17.629  exe              54827  54808    0 /proc/self/exe init\n17.664  systemd-sysctl   54832  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7f2e47d --prefix=/net/ipv4/neigh/veth7f2e47d --prefix=/net/ipv6/conf/veth7f2e47d --prefix=/net/ipv6/neigh/veth7f2e47d\n17.679  exe              54838  54808    0 /proc/1599/exe -exec-root=/var/run/docker 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 d7da31e8f8e1\n17.699  exe              54846  1599     0 /proc/self/exe /var/run/docker/netns/3e401da5d4b2 all false\n17.758  runc             54864  54798    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --log-format json --systemd-cgroup start 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10\n17.764  sh               54831  54798    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.765  cargo            54870  54831    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n17.775  cargo-native-tr  54870  54831    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n17.778  cargo            54871  54870    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.788  rustc            54872  54871    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.800  rustc            54874  54871    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.809  runc             54878  49386    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b --log-format json --systemd-cgroup kill --all bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888 9\n17.826  runc             54885  49386    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b --log-format json --systemd-cgroup delete bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888\n17.838  execsnoop        54891  54870    0 /usr/local/bin/execsnoop -t\n17.839  python3          54891  54870    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.852  runc             54894  49353    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 --log-format json --systemd-cgroup kill --all a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7 9\n17.870  runc             54901  49353    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 --log-format json --systemd-cgroup delete a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7\n18.047  containerd-shim  54907  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b delete\n18.049  runc             54914  54907    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf788 --log-format json delete --force bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888\n18.086  systemd-sysctl   54919  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethfb8276c --prefix=/net/ipv4/neigh/vethfb8276c --prefix=/net/ipv6/conf/vethfb8276c --prefix=/net/ipv6/neigh/vethfb8276c\n18.094  containerd-shim  54921  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 delete\n18.096  runc             54928  54921    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f --log-format json delete --force a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7\n18.140  systemd-sysctl   54933  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth651aca6 --prefix=/net/ipv4/neigh/veth651aca6 --prefix=/net/ipv6/conf/veth651aca6 --prefix=/net/ipv6/neigh/veth651aca6\n18.206  runc             54934  49256    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 --log-format json --systemd-cgroup kill --all f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96 9\n18.223  runc             54940  49256    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 --log-format json --systemd-cgroup delete f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96\n18.403  containerd-shim  54946  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 delete\n18.406  runc             54953  54946    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da9 --log-format json delete --force f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96\n18.443  systemd-sysctl   54959  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd600a16 --prefix=/net/ipv4/neigh/vethd600a16 --prefix=/net/ipv6/conf/vethd600a16 --prefix=/net/ipv6/neigh/vethd600a16\n18.511  runc             54961  49929    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d --log-format json --systemd-cgroup kill --all 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637 9\n18.518  runc             54967  49929    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d --log-format json --systemd-cgroup delete 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637\n18.698  containerd-shim  54974  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d delete\n18.700  runc             54981  54974    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d9863 --log-format json delete --force 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637\n18.735  systemd-sysctl   54986  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5b8f709 --prefix=/net/ipv4/neigh/veth5b8f709 --prefix=/net/ipv6/conf/veth5b8f709 --prefix=/net/ipv6/neigh/veth5b8f709\n18.846  sh               54987  2147557   0 /bin/sh -c which ps\n18.847  which            54987  2147557   0 /usr/bin/which ps\n18.849  sh               54988  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.850  ps               54988  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.875  sh               54989  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n18.876  cpuUsage.sh      54989  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n18.877  sed              54990  54989    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.879  cat              54991  54989    0 /usr/bin/cat /proc/2240539/stat\n18.880  cat              54992  54989    0 /usr/bin/cat /proc/4193716/stat\n18.881  sleep            54993  54989    0 /usr/bin/sleep 1\n19.274  cargo            54994  54641    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n19.287  rustc            54995  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n19.316  rustc            55001  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n19.357  cc               55024  55001    0 /tmp/native-trace-54641-1783992801298/shims/cc -m64 /target/debug/build/valuable-0ca3a52e87f47781/rustcum31Fu/symbols.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2bcuvqydoknozqmp1me20ruil.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2hvolwvrh1z7h0esed9fdlkq6.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2ydqatcbwpyv0nfser2rvjw0s.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.320kk89i2c31bqlrt1pe5ftwu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.3dorb0xb6tyxiuzsrh06fg7wn.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.44p8ua3isbvp2so96dfqsrcv0.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.4mgnn3dy9r06fb4dhef909zhp.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54olwytbg728sxv8s6jzea9ac.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54xlj1thl6ekctt4ryak72mpk.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5gyye0zaqcjlw0qa72458hp4p.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5m686vmv93io6lluiiyhiylju.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.7d19io80brmbzee20rw5urjmi.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.b7inlg8jykc014dunu01jjkqu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.c3a0y0h3kjig5bmjwukot6pmm.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.deexadt1dri1ihovsh8z1lp29.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.dlbacscotl41na11230m8gkv8.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.e0jqet5ubfmmb5vnbm2c21wdk.15hdgiv.rcgu.o ...\n19.357  cc               55025  55024    0 /usr/bin/cc -m64 /target/debug/build/valuable-0ca3a52e87f47781/rustcum31Fu/symbols.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2bcuvqydoknozqmp1me20ruil.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2hvolwvrh1z7h0esed9fdlkq6.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2ydqatcbwpyv0nfser2rvjw0s.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.320kk89i2c31bqlrt1pe5ftwu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.3dorb0xb6tyxiuzsrh06fg7wn.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.44p8ua3isbvp2so96dfqsrcv0.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.4mgnn3dy9r06fb4dhef909zhp.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54olwytbg728sxv8s6jzea9ac.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54xlj1thl6ekctt4ryak72mpk.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5gyye0zaqcjlw0qa72458hp4p.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5m686vmv93io6lluiiyhiylju.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.7d19io80brmbzee20rw5urjmi.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.b7inlg8jykc014dunu01jjkqu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.c3a0y0h3kjig5bmjwukot6pmm.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.deexadt1dri1ihovsh8z1lp29.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.dlbacscotl41na11230m8gkv8.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.e0jqet5ubfmmb5vnbm2c21wdk.15hdgiv.rcgu.o ...\n19.360  collect2         55026  55025    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.361  ld.lld           55027  55026    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781 ...\n19.362  rust-lld         55027  55026    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.400  build-script-bu  55045  54994    0 /target/debug/build/valuable-0ca3a52e87f47781/build-script-build\n19.404  rustc            55047  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name valuable --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n19.684  cargo            55059  54870    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n19.697  rustc            55070  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n19.722  rustc            55113  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n19.722  rustc            55111  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.18/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=ba1b82e103e0280b ...\n19.821  cc               55188  55113    0 /tmp/native-trace-54870-1783992801742/shims/cc -m64 /target/debug/build/proc-macro2-46239aad0aaf2dde/rustcz8FJmv/symbols.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0bv3et31ep2k9sd4r4xv6yltt.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0edhhq7oafgl2yf0nrxumcg9r.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0g0902jm3uya6wioho7beok0j.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0owef7ksnbk6ukcc2242nefkr.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0rdzizyhqamtksvgo7enpq5az.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1r69zij4wcxunk2gd17a0kpg6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1sghvgwc08k4idxie37yo3pw0.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1wbfjtyvleo9dhvql6dw9ezks.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2om80ctxk1ydfs1240ujhhg0b.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2ylb2sbb9n609gy1nl3eivm1m.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.34jg2bcz8z6kfpvajxful9pig.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3dgkawms7tf7icnefiv8uh2ur.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3h5kxyomdhio13fti327b3ul4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3pfht32bkan9uc6xs96laffv6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3vy5vc4kvl4zobt41ffusuic4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3wfb4bv7o9ei3djc1ma3hgool.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.4sen9su2ywavj025286hzh4rs.0uq14k2.rcgu.o ...\n19.822  cc               55189  55188    0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-46239aad0aaf2dde/rustcz8FJmv/symbols.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0bv3et31ep2k9sd4r4xv6yltt.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0edhhq7oafgl2yf0nrxumcg9r.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0g0902jm3uya6wioho7beok0j.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0owef7ksnbk6ukcc2242nefkr.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0rdzizyhqamtksvgo7enpq5az.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1r69zij4wcxunk2gd17a0kpg6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1sghvgwc08k4idxie37yo3pw0.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1wbfjtyvleo9dhvql6dw9ezks.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2om80ctxk1ydfs1240ujhhg0b.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2ylb2sbb9n609gy1nl3eivm1m.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.34jg2bcz8z6kfpvajxful9pig.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3dgkawms7tf7icnefiv8uh2ur.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3h5kxyomdhio13fti327b3ul4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3pfht32bkan9uc6xs96laffv6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3vy5vc4kvl4zobt41ffusuic4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3wfb4bv7o9ei3djc1ma3hgool.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.4sen9su2ywavj025286hzh4rs.0uq14k2.rcgu.o ...\n19.826  collect2         55190  55189    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.827  ld.lld           55191  55190    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde ...\n19.828  rust-lld         55191  55190    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.883  sed              55209  54989    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n19.883  build-script-bu  55210  55059    0 /target/debug/build/proc-macro2-46239aad0aaf2dde/build-script-build\n19.885  cat              55211  54989    0 /usr/bin/cat /proc/2240539/stat\n19.885  rustc            55212  55210    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n19.886  cat              55214  54989    0 /usr/bin/cat /proc/4193716/stat\n19.895  rustc            55217  55210    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-1a2ad12dc9160ce7/out/probe build/probe.rs --target aarch64-unknown-linux-gnu\n19.922  rustc            55222  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n20.487  cross            55331  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.488  rustc            55334  55331    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.509  rustc            55334  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.521  rustc            55346  55331    0 /home/xmoe/.cargo/bin/rustc -vV\n20.542  rustc            55346  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.552  cargo            55356  55331    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.573  cargo            55356  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.584  rustc            55366  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.586  git              55365  2235138   0 /usr/bin/git config --get commit.template\n20.593  rustc            55368  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.601  git              55369  2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n20.604  rustc            55373  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.617  git              55374  2235138   0 /usr/bin/git status -z -uall\n20.629  rustc            55379  55331    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n20.632  git              55378  2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n20.651  rustc            55379  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n20.662  docker           55391  55331    0 /usr/bin/docker --help\n20.674  docker           55402  55331    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n20.686  runc             55412  1599     0 /usr/bin/runc --version\n20.689  docker-init      55418  1599     0 /usr/bin/docker-init --version\n20.690  docker           55419  55331    0 /usr/bin/docker info -f {{.SecurityOptions}}\n20.701  runc             55430  1599     0 /usr/bin/runc --version\n20.704  docker-init      55436  1599     0 /usr/bin/docker-init --version\n20.725  rustup           55440  55331    0 /home/xmoe/.cargo/bin/rustup toolchain list\n20.746  rustup           55449  55331    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n20.767  rustup           55458  55331    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n20.791  uname            55467  55331    0 /usr/bin/uname -r\n20.806  docker           55468  55331    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n20.842  systemd-sysctl   55483  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8170368 --prefix=/net/ipv4/neigh/veth8170368 --prefix=/net/ipv6/conf/veth8170368 --prefix=/net/ipv6/neigh/veth8170368\n20.842  systemd-sysctl   55482  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth81dd9a9 --prefix=/net/ipv4/neigh/veth81dd9a9 --prefix=/net/ipv6/conf/veth81dd9a9 --prefix=/net/ipv6/neigh/veth81dd9a9\n20.856  containerd-shim  55484  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 start\n20.859  containerd-shim  55491  55484    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 -address /var/run/docker/containerd/containerd.sock\n20.863  runc             55501  55491    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956\n20.867  exe              55509  55501    0 /proc/self/exe init\n20.885  cross            55513  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n20.887  rustc            55520  55513    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.891  rustc            55520  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.901  exe              55532  55501    0 /proc/1599/exe -exec-root=/var/run/docker 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 d7da31e8f8e1\n20.903  rustc            55539  55513    0 /home/xmoe/.cargo/bin/rustc -vV\n20.907  rustc            55539  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.913  cross            55549  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n20.914  rustc            55552  55549    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.917  cargo            55561  55513    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.918  cross            55564  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.919  rustc            55567  55564    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.920  exe              55576  1599     0 /proc/self/exe /var/run/docker/netns/8b628a44607d all false\n20.922  cargo            55561  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.924  rustc            55567  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.933  rustc            55596  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.936  rustc            55597  55564    0 /home/xmoe/.cargo/bin/rustc -vV\n20.940  rustc            55552  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.941  rustc            55597  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.942  rustc            55607  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.949  cargo            55614  55564    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.951  rustc            55616  55549    0 /home/xmoe/.cargo/bin/rustc -vV\n20.952  rustc            55625  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.954  cargo            55614  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.965  rustc            55637  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.967  runc             55639  55491    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --log-format json --systemd-cgroup start 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956\n20.972  sh               55511  55491    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n20.973  cargo            55646  55511    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n20.975  rustc            55647  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.977  rustc            55616  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.985  cargo-native-tr  55646  55511    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n20.986  cargo            55652  55549    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.987  rustc            55653  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.989  cargo            55654  55646    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n20.999  rustc            55666  55654    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.008  cargo            55652  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n21.011  rustc            55668  55654    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.019  rustc            55670  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.028  rustc            55674  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.040  rustc            55678  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.076  git              55683  2235138   0 /usr/bin/git worktree list --porcelain\n21.114  cross            55684  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n21.115  rustc            55687  55684    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.120  rustc            55687  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.131  runc             55701  47737    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a --log-format json --systemd-cgroup kill --all 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9 9\n21.131  rustc            55700  55684    0 /home/xmoe/.cargo/bin/rustc -vV\n21.136  rustc            55700  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.145  cargo            55716  55684    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.148  runc             55725  47737    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a --log-format json --systemd-cgroup delete 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9\n21.149  cargo            55716  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.160  rustc            55731  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.169  rustc            55733  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.192  rustc            55737  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.277  runc             55741  49799    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e --log-format json --systemd-cgroup kill --all f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e 9\n21.284  runc             55748  49799    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e --log-format json --systemd-cgroup delete f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e\n21.364  containerd-shim  55754  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a delete\n21.367  runc             55761  55754    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a --log-format json delete --force 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9\n21.369  runc             55767  50023    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc --log-format json --systemd-cgroup kill --all a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0 9\n21.386  runc             55773  50023    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc --log-format json --systemd-cgroup delete a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0\n21.408  systemd-sysctl   55779  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethae76c09 --prefix=/net/ipv4/neigh/vethae76c09 --prefix=/net/ipv6/conf/vethae76c09 --prefix=/net/ipv6/neigh/vethae76c09\n21.471  runc             55780  50289    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d67 --log-format json --systemd-cgroup kill --all 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb 9\n21.488  runc             55786  50289    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d67 --log-format json --systemd-cgroup delete 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb\n21.520  cross            55792  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n21.521  rustc            55795  55792    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.526  rustc            55795  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.537  rustc            55807  55792    0 /home/xmoe/.cargo/bin/rustc -vV\n21.542  rustc            55807  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.545  containerd-shim  55816  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e delete\n21.547  runc             55822  55816    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1 --log-format json delete --force f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e\n21.549  cross            55829  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n21.550  rustc            55832  55829    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.551  cargo            55833  55792    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.555  rustc            55832  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.555  cargo            55833  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.565  rustc            55853  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.567  rustc            55854  55829    0 /home/xmoe/.cargo/bin/rustc -vV\n21.572  rustc            55854  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.574  rustc            55864  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.581  cargo            55869  55829    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.583  systemd-sysctl   55870  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethddd6c57 --prefix=/net/ipv4/neigh/vethddd6c57 --prefix=/net/ipv6/conf/vethddd6c57 --prefix=/net/ipv6/neigh/vethddd6c57\n21.585  containerd-shim  55880  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc delete\n21.586  rustc            55884  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.586  cargo            55869  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.587  runc             55887  55880    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f --log-format json delete --force a83577acc3bdb608716d9dea99309a25669e4c3e6f832a51091b6cfaabc762f0\n21.596  rustc            55896  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.605  rustc            55898  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.617  rustc            55902  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.625  systemd-sysctl   55903  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf192d49 --prefix=/net/ipv4/neigh/vethf192d49 --prefix=/net/ipv6/conf/vethf192d49 --prefix=/net/ipv6/neigh/vethf192d49\n21.712  containerd-shim  55908  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d67 delete\n21.714  runc             55915  55908    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7c --log-format json delete --force 44659eaa4c108fb80f307528d215c3a53f41402ac4daee17ed3cdeb0d671f7cb\n21.746  systemd-sysctl   55920  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7b4cddd --prefix=/net/ipv4/neigh/veth7b4cddd --prefix=/net/ipv6/conf/veth7b4cddd --prefix=/net/ipv6/neigh/veth7b4cddd\n22.883  rustc            55925  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.932  rustc            55927  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n22.959  rustc            55929  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.007  rustc            55931  55833    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.058  rustc            55933  55869    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.129  rustc            55935  55564    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.130  rustc            55936  55513    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.134  rustc            55935  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.134  rustc            55936  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.135  rustc            55953  55549    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.136  execsnoop        55954  55646    0 /usr/local/bin/execsnoop -t\n23.136  python3          55954  55646    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n23.145  docker           55971  55564    0 /usr/bin/docker --help\n23.145  docker           55972  55513    0 /usr/bin/docker --help\n23.157  docker           55991  55513    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.158  rustc            55953  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.158  docker           55992  55564    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.160  rustc            55998  55829    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.165  rustc            55998  55829    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.170  runc             56022  1599     0 /usr/bin/runc --version\n23.170  runc             56023  1599     0 /usr/bin/runc --version\n23.172  rustc            56034  55792    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.173  docker-init      56035  1599     0 /usr/bin/docker-init --version\n23.173  docker-init      56036  1599     0 /usr/bin/docker-init --version\n23.174  docker           56039  55564    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.174  docker           56040  55549    0 /usr/bin/docker --help\n23.175  docker           56045  55513    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.179  docker           56066  55829    0 /usr/bin/docker --help\n23.179  rustc            56034  55792    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.187  runc             56091  1599     0 /usr/bin/runc --version\n23.188  runc             56092  1599     0 /usr/bin/runc --version\n23.188  docker           56093  55549    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.191  docker           56110  55792    0 /usr/bin/docker --help\n23.191  docker-init      56109  1599     0 /usr/bin/docker-init --version\n23.193  docker           56111  55829    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.194  docker-init      56112  1599     0 /usr/bin/docker-init --version\n23.195  rustc            56120  55684    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.201  rustc            56120  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.204  runc             56144  1599     0 /usr/bin/runc --version\n23.205  runc             56150  1599     0 /usr/bin/runc --version\n23.207  docker           56155  55792    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.207  docker-init      56157  1599     0 /usr/bin/docker-init --version\n23.208  docker           56158  55549    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.208  docker-init      56159  1599     0 /usr/bin/docker-init --version\n23.210  docker           56174  55829    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.214  docker           56183  55684    0 /usr/bin/docker --help\n23.219  rustup           56204  55513    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.219  rustup           56205  55564    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.221  runc             56206  1599     0 /usr/bin/runc --version\n23.221  runc             56207  1599     0 /usr/bin/runc --version\n23.223  runc             56237  1599     0 /usr/bin/runc --version\n23.224  docker-init      56238  1599     0 /usr/bin/docker-init --version\n23.224  docker-init      56244  1599     0 /usr/bin/docker-init --version\n23.225  docker           56245  55792    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.226  rustup           56246  55513    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.226  rustup           56247  55564    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.226  docker-init      56248  1599     0 /usr/bin/docker-init --version\n23.228  docker           56254  55684    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.239  runc             56288  1599     0 /usr/bin/runc --version\n23.241  runc             56294  1599     0 /usr/bin/runc --version\n23.243  docker-init      56300  1599     0 /usr/bin/docker-init --version\n23.244  docker-init      56301  1599     0 /usr/bin/docker-init --version\n23.246  docker           56302  55684    0 /usr/bin/docker info -f {{.SecurityOptions}}\n23.251  rustup           56308  55829    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.252  rustup           56309  55513    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.255  rustup           56318  55549    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.257  rustup           56334  55564    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.260  runc             56342  1599     0 /usr/bin/runc --version\n23.262  rustup           56354  55829    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.263  docker-init      56355  1599     0 /usr/bin/docker-init --version\n23.268  rustup           56364  55792    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.274  rustup           56373  55792    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.279  uname            56382  55513    0 /usr/bin/uname -r\n23.285  uname            56383  55564    0 /usr/bin/uname -r\n23.288  rustup           56384  55549    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.290  rustup           56385  55829    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.294  rustup           56402  55684    0 /home/xmoe/.cargo/bin/rustup toolchain list\n23.300  rustup           56411  55792    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.301  docker           56413  55513    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.302  rustup           56412  55684    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n23.304  docker           56427  55564    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.314  rustup           56452  55549    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.319  uname            56461  55829    0 /usr/bin/uname -r\n23.328  runc             56462  49987    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b --log-format json --systemd-cgroup kill --all 8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b31584 9\n23.329  uname            56463  55792    0 /usr/bin/uname -r\n23.330  rustup           56469  55684    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n23.337  runc             56478  49987    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b --log-format json --systemd-cgroup delete 8c48427cf3cedf2171ea2c440955a8252a180d7bdcb0672459398bac01b31584\n23.343  docker           56484  55829    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.346  uname            56490  55549    0 /usr/bin/uname -r\n23.349  systemd-sysctl   56491  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb7e39a3 --prefix=/net/ipv4/neigh/vethb7e39a3 --prefix=/net/ipv6/conf/vethb7e39a3 --prefix=/net/ipv6/neigh/vethb7e39a3\n23.350  systemd-sysctl   56492  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth22901f8 --prefix=/net/ipv4/neigh/veth22901f8 --prefix=/net/ipv6/conf/veth22901f8 --prefix=/net/ipv6/neigh/veth22901f8\n23.352  docker           56494  55792    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.354  systemd-sysctl   56497  54510    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth17a9353 --prefix=/net/ipv4/neigh/veth17a9353 --prefix=/net/ipv6/conf/veth17a9353 --prefix=/net/ipv6/neigh/veth17a9353\n23.355  systemd-sysctl   56496  54522    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth48cca07 --prefix=/net/ipv4/neigh/veth48cca07 --prefix=/net/ipv6/conf/veth48cca07 --prefix=/net/ipv6/neigh/veth48cca07\n23.363  uname            56504  55684    0 /usr/bin/uname -r\n23.370  docker           56507  55549    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.371  containerd-shim  56508  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a978af6b start\n23.376  containerd-shim  56520  56508    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a978af6b -address /var/run/docker/containerd/containerd.sock\n23.379  runc             56530  56520    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a97 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a97 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a97 42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a978af6b\n23.386  exe              56541  56530    0 /proc/self/exe init\n23.387  docker           56543  55684    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n23.419  exe              56568  56530    0 /proc/1599/exe -exec-root=/var/run/docker 42d7ca641735b9d2c912da64026d388646863ab056190c22151c5fe2a978af6b d7da31e8f8e1\n23.439  exe              56576  1599     0 /proc/self/exe /var/run/docker/netns/952f96b918e5 all false\n"
    },
    {
      "argv": [],
      "build_script_related": true,
      "build_script_root_pid": 52088,
      "build_script_target_dir": "libc-c3c858474dcfa7e6",
      "comm": "rustc",
      "event": "process_exec",
      "image": "rustc",
      "pid": 52105,
      "ppid": 52088,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52088,
      "build_script_target_dir": "libc-c3c858474dcfa7e6",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/libc-c3c858474dcfa7e6/build-script-build",
      "pid": 52088,
      "ppid": 51426,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/ring-36133a68ed4b831a/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/ring-36133a68ed4b831a/build-script-build",
      "pid": 52478,
      "ppid": 51426,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-E",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/13880850535424185224detect_compiler_family.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 52479,
      "ppid": 52478,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-E",
        "-quiet",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/13880850535424185224detect_compiler_family.c",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-dumpbase",
        "13880850535424185224detect_compiler_family.c",
        "-dumpbase-ext",
        ".c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 52480,
      "ppid": 52479,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 52482,
      "ppid": 52478,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 52483,
      "ppid": 52478,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/curve25519/curve25519.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
        "-dumpbase",
        "fad98b632b8ce3cc-curve25519.c",
        "-dumpbase-ext",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 52484,
      "ppid": 52483,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/fad98b632b8ce3cc-curve25519.o",
        "/tmp/ccvqDvzH.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 52500,
      "ppid": 52483,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 52522,
      "ppid": 52478,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/aes/aes_nohw.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
        "-dumpbase",
        "ca4b6ef5433f5aeb-aes_nohw.c",
        "-dumpbase-ext",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 52523,
      "ppid": 52522,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/ca4b6ef5433f5aeb-aes_nohw.o",
        "/tmp/ccdmfLIU.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 52527,
      "ppid": 52522,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "cc1",
      "pid": 52537,
      "ppid": 52535,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 52535,
      "ppid": 52478,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/ca8bd8684bb569fa-montgomery.o",
        "/tmp/cctFwzKT.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 52540,
      "ppid": 52535,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 52541,
      "ppid": 52478,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/bn/montgomery_inv.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
        "-dumpbase",
        "ca8bd8684bb569fa-montgomery_inv.c",
        "-dumpbase-ext",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 52542,
      "ppid": 52541,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/ca8bd8684bb569fa-montgomery_inv.o",
        "/tmp/ccgr0S76.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 52544,
      "ppid": 52541,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 52545,
      "ppid": 52478,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/ec/ecp_nistz.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
        "-dumpbase",
        "a9af75d892b04b75-ecp_nistz.c",
        "-dumpbase-ext",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 52547,
      "ppid": 52545,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-ecp_nistz.o",
        "/tmp/cc0oG8eG.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 52549,
      "ppid": 52545,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 52550,
      "ppid": 52478,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/ec/gfp_p256.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
        "-dumpbase",
        "a9af75d892b04b75-gfp_p256.c",
        "-dumpbase-ext",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 52551,
      "ppid": 52550,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-gfp_p256.o",
        "/tmp/ccDvElmp.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 52552,
      "ppid": 52550,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 52553,
      "ppid": 52478,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/ec/gfp_p384.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
        "-dumpbase",
        "a9af75d892b04b75-gfp_p384.c",
        "-dumpbase-ext",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 52554,
      "ppid": 52553,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-gfp_p384.o",
        "/tmp/ccpLQk4K.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 52560,
      "ppid": 52553,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 52562,
      "ppid": 52478,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/fipsmodule/ec/p256.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
        "-dumpbase",
        "a9af75d892b04b75-p256.c",
        "-dumpbase-ext",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 52564,
      "ppid": 52562,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-p256.o",
        "/tmp/ccmwAhtu.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 52576,
      "ppid": 52562,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 52578,
      "ppid": 52478,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/limbs/limbs.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
        "-dumpbase",
        "a1949f2101df4b9c-limbs.c",
        "-dumpbase-ext",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 52579,
      "ppid": 52578,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a1949f2101df4b9c-limbs.o",
        "/tmp/cc8E5cjT.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 52584,
      "ppid": 52578,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 52587,
      "ppid": 52478,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/mem.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
        "-dumpbase",
        "7effb53edfc7fa2d-mem.c",
        "-dumpbase-ext",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 52590,
      "ppid": 52587,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/7effb53edfc7fa2d-mem.o",
        "/tmp/cc5vAgys.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 52595,
      "ppid": 52587,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 52602,
      "ppid": 52478,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/poly1305/poly1305.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
        "-dumpbase",
        "bec76f70393ddef1-poly1305.c",
        "-dumpbase-ext",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 52606,
      "ppid": 52602,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/bec76f70393ddef1-poly1305.o",
        "/tmp/ccIZ14KA.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 52618,
      "ppid": 52602,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-ar",
        "cq",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/libring_core_0_17_8_.a",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/fad98b632b8ce3cc-curve25519.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/ca4b6ef5433f5aeb-aes_nohw.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/ca8bd8684bb569fa-montgomery.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/ca8bd8684bb569fa-montgomery_inv.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-ecp_nistz.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-gfp_p256.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-gfp_p384.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a9af75d892b04b75-p256.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/a1949f2101df4b9c-limbs.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/7effb53edfc7fa2d-mem.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/bec76f70393ddef1-poly1305.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-ar",
      "pid": 52626,
      "ppid": 52478,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-ar",
        "s",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/libring_core_0_17_8_.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-ar",
      "pid": 52631,
      "ppid": 52478,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-E",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/16141142337147692699detect_compiler_family.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 52635,
      "ppid": 52478,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-E",
        "-quiet",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/16141142337147692699detect_compiler_family.c",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-dumpbase",
        "16141142337147692699detect_compiler_family.c",
        "-dumpbase-ext",
        ".c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 52636,
      "ppid": 52635,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 52639,
      "ppid": 52478,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-Wall",
        "-Wextra",
        "-fvisibility=hidden",
        "-std=c1x",
        "-Wall",
        "-Wbad-function-cast",
        "-Wcast-align",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 52640,
      "ppid": 52478,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "-dD",
        "-D",
        "NDEBUG",
        "crypto/constant_time_test.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/",
        "-dumpbase",
        "7effb53edfc7fa2d-constant_time_test.c",
        "-dumpbase-ext",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 52641,
      "ppid": 52640,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-I",
        "include",
        "-I",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/7effb53edfc7fa2d-constant_time_test.o",
        "/tmp/ccbaU115.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 52642,
      "ppid": 52640,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-ar",
        "cq",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/libring_core_0_17_8_test.a",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/7effb53edfc7fa2d-constant_time_test.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-ar",
      "pid": 52643,
      "ppid": 52478,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-ar",
        "s",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/ring-0311355296b3aa94/out/libring_core_0_17_8_test.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52478,
      "build_script_target_dir": "ring-36133a68ed4b831a",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-ar",
      "pid": 52645,
      "ppid": 52478,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/rustls-2216ddcaf0bdcdf8/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52652,
      "build_script_target_dir": "rustls-2216ddcaf0bdcdf8",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build-script-build",
      "pid": 52652,
      "ppid": 51426,
      "root_cargo_pid": 51426,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "rustls",
      "cwd": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
      "event_id": "bsrun:2aaa3dada998f4ea:aa8e620880ea118c:01382d2620d23103",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/rustls-2216ddcaf0bdcdf8/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
      "out_dir": "/target/debug/build/rustls-2216ddcaf0bdcdf8/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
      "success": true,
      "target": null,
      "version": "0.21.12",
      "_owner": {
        "crate": "rustls",
        "version": "0.21.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12#rustls@0.21.12",
        "manifest_dir": "/tmp/crate-build-riscv64-ti69japl/src/rustls-0.21.12",
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
      "argv": [],
      "build_script_related": true,
      "build_script_root_pid": 52088,
      "build_script_target_dir": "libc-c3c858474dcfa7e6",
      "comm": "rustc",
      "event": "process_exec",
      "image": "rustc",
      "pid": 52105,
      "ppid": 52088,
      "root_cargo_pid": 51426,
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
