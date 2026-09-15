# `io-uring` `0.7.9`

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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
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
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu",
    "/target/debug/build/io-uring-ea6b6ff132ca8689",
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
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-306953-1783993829801347974.map",
  "pid": 306953,
  "ppid": 306888,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-306953-1783993829801347974.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
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
  "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "workspace_root": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#anyhow@1.0.86",
      "name": "anyhow",
      "version": "1.0.86",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anyhow-1.0.86/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anyhow-1.0.86"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.3.0",
      "name": "autocfg",
      "version": "1.3.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.3.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.6.0",
      "name": "bitflags",
      "version": "2.6.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.6.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.6.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
      "name": "cfg-if",
      "version": "1.0.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0"
    },
    {
      "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
      "name": "io-uring",
      "version": "0.7.9",
      "manifest_path": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
      "name": "libc",
      "version": "0.2.156",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#slab@0.4.9",
      "name": "slab",
      "version": "0.4.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#socket2@0.5.7",
      "name": "socket2",
      "version": "0.5.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/socket2-0.5.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/socket2-0.5.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.52.0",
      "name": "windows-sys",
      "version": "0.52.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.52.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.52.0"
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
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "exit_code": 0,
  "kind": "exec",
  "pid": 306953,
  "ppid": 306888,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "io-uring",
  "cargo_pkg_version": "0.7.9",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "event_id": "used:cc:68232c9559a91bb5:3aa7eaa3b713ccc3:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
  "pid": 306953,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "io-uring",
  "cargo_pkg_version": "0.7.9",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "event_id": "used:cc:68232c9559a91bb5:53efe489880addb5:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
  "pid": 306953,
  "sha256": "bf6b59b4e3c99abaabb968b8ef4de0cf27f9d51afe5a1aee8826ffa0f36ba95f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "io-uring",
  "cargo_pkg_version": "0.7.9",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "event_id": "used:cc:68232c9559a91bb5:5dc6ddddfc7207e5:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
  "pid": 306953,
  "sha256": "73b560f9d258462e97ac0b121ece6387528181283743c662f8a5a32e8fe54970",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "io-uring",
  "cargo_pkg_version": "0.7.9",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "event_id": "used:cc:68232c9559a91bb5:80bf3885172142d7:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
  "pid": 306953,
  "sha256": "8e60849e2e1fa2882bdce1af13785c26e41dbc0a8236fe03f0b50bcdd3a797ae",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "io-uring",
  "cargo_pkg_version": "0.7.9",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "event_id": "used:cc:68232c9559a91bb5:5ad62714990aca26:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
  "pid": 306953,
  "sha256": "1c2d8c3bee2c30f913a81ac55ee66f7a17e8baa63f1dee6910366cef396628b9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "io-uring",
  "cargo_pkg_version": "0.7.9",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "event_id": "used:cc:68232c9559a91bb5:e41b13ee82538241:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
  "pid": 306953,
  "sha256": "833bd7df179cc96ce4c36692b7cc587abbc4c6ec31c49e00b71a7f1b0d21d769",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "io-uring",
  "cargo_pkg_version": "0.7.9",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "event_id": "used:cc:68232c9559a91bb5:d5de41d760e2f9f7:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
  "pid": 306953,
  "sha256": "bae7432832fe963def547d3943c9d93a0232bf96a891e44d192fc8b34ab39896",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "io-uring",
  "cargo_pkg_version": "0.7.9",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "event_id": "used:cc:68232c9559a91bb5:18397aba03f9d7bc:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
  "pid": 306953,
  "sha256": "19fb2eeea9364d7061347a67eb332563a7bbc8fc2340cd95e11b69ef53605881",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
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
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "cargo_pkg_name": "io-uring",
  "cargo_pkg_version": "0.7.9",
  "context_path": "/tmp/native-trace-306534-1783993825592/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-306534-1783993825592/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 306953,
  "ppid": 306888,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu",
    "/target/debug/build/io-uring-ea6b6ff132ca8689",
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
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-306953-1783993829801347974.map",
  "pid": 306953,
  "ppid": 306888,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-306953-1783993829801347974.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
  "exit_code": 0,
  "kind": "exec",
  "pid": 306987,
  "ppid": 306881,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.156",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.156",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
  "event_id": "used:cc:bf4e8db12c663bbd:841a833fb42f1ec0:c338943aef9d968a",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
  "path": "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
  "pid": 306987,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.156",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.156",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
  "event_id": "used:cc:bf4e8db12c663bbd:c351fdf3b90cd87c:c338943aef9d968a",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
  "path": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
  "pid": 306987,
  "sha256": "cbff5439c75a325335168109f20812815f73bb83aa61b6a39fc0e85c9630736f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.156",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.156",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
  "event_id": "used:cc:bf4e8db12c663bbd:f5df9fdcfd49e411:c338943aef9d968a",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
  "path": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
  "pid": 306987,
  "sha256": "74114b97c4c1a2a2fdaa1fa79131ee09c3ef2cf13f76d162a3dc6f8ae200ba31",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.156",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.156",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
  "event_id": "used:cc:bf4e8db12c663bbd:606c2cc26e257c19:c338943aef9d968a",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
  "path": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
  "pid": 306987,
  "sha256": "c692600706608b1e9eabffd7d767acfc1d3c6acbe697570721bc0134a564ed00",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.156",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.156",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
  "event_id": "used:cc:bf4e8db12c663bbd:c3f5f7670c879a45:c338943aef9d968a",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
  "path": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
  "pid": 306987,
  "sha256": "36ecc7e54d00c83fc17a4733a461ba67af8a95446b620a081829593ce43b942f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.156",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/raw-dylibs",
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
  "output": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.156",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.156",
  "context_path": "/tmp/native-trace-306534-1783993825592/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-306534-1783993825592/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 306987,
  "ppid": 306881,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "_owner": {
    "crate": "libc",
    "version": "0.2.156",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN",
    "/target/debug/build/libc-1f865bb516326eef",
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
      "directory": "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN",
      "kind": "object",
      "path": "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-1f865bb516326eef",
      "kind": "object",
      "path": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-1f865bb516326eef",
      "kind": "object",
      "path": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-1f865bb516326eef",
      "kind": "object",
      "path": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-1f865bb516326eef",
      "kind": "object",
      "path": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-306987-1783993830001112262.map",
  "pid": 306987,
  "ppid": 306881,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-306987-1783993830001112262.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "libc",
    "version": "0.2.156",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 23

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

#### Record 24

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 1,
  "parsed_event_count": 480,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 481,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "/rustc --print sysroot\n12.406  docker-init      307797 1599     0 /usr/bin/docker-init --version\n12.411  docker           307811 307618   0 /usr/bin/docker info -f {{.SecurityOptions}}\n12.415  rustc            307796 307664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n12.415  rustc            307795 307727   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n12.441  runc             307830 1599     0 /usr/bin/runc --version\n12.441  docker           307832 307727   0 /usr/bin/docker --help\n12.441  docker           307831 307664   0 /usr/bin/docker --help\n12.448  docker-init      307848 1599     0 /usr/bin/docker-init --version\n12.464  docker           307854 307727   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n12.476  docker           307861 307664   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n12.491  runc             307874 1599     0 /usr/bin/runc --version\n12.499  runc             307879 1599     0 /usr/bin/runc --version\n12.504  docker-init      307885 1599     0 /usr/bin/docker-init --version\n12.507  docker-init      307887 1599     0 \n12.507  docker           307886 307664   0 /usr/bin/docker info -f {{.SecurityOptions}}\n12.512  docker           307893 307727   0 /usr/bin/docker info -f {{.SecurityOptions}}\n12.515  rustup           307895 307618   0 /home/xmoe/.cargo/bin/rustup toolchain list\n12.525  rustup           307910 307618   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n12.525  runc             307911 1599     0 /usr/bin/runc --version\n12.530  docker-init      307925 1599     0 /usr/bin/docker-init --version\n12.562  cross            307929 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n12.563  rustc            307932 307929   0 /home/xmoe/.cargo/bin/rustc --print target-list\n12.565  rustup           307933 307618   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n12.567  rustup           307939 307664   0 /home/xmoe/.cargo/bin/rustup toolchain list\n12.569  runc             307946 1599     0 /usr/bin/runc --version\n12.572  rustc            307932 307929   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n12.576  rustup           307963 307664   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n12.590  rustc            307978 307929   0 /home/xmoe/.cargo/bin/rustc -vV\n12.598  rustc            307978 307929   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n12.605  docker-init      307987 1599     0 /usr/bin/docker-init --version\n12.605  uname            307988 307618   0 /usr/bin/uname -r\n12.616  rustup           307991 307664   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n12.616  cargo            307990 307929   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n12.641  cargo            307990 307929   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n12.641  docker           308008 307618   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n12.655  rustc            308017 307990   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n12.657  uname            308018 307664   0 /usr/bin/uname -r\n12.660  rustup           308019 307727   0 /home/xmoe/.cargo/bin/rustup toolchain list\n12.669  rustup           308031 307727   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n12.672  rustc            308032 307990   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n12.724  docker           308044 307664   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n12.737  rustup           308046 307727   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n12.737  rustc            308050 307990   0 \n12.774  uname            308067 307727   0 /usr/bin/uname -r\n12.802  docker           308068 307727   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n12.830  systemd-sysctl   308081 307553   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethbf5d69b --prefix=/net/ipv4/neigh/vethbf5d69b --prefix=/net/ipv6/conf/vethbf5d69b --prefix=/net/ipv6/neigh/vethbf5d69b\n12.830  systemd-sysctl   308082 307602   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth25c720b --prefix=/net/ipv4/neigh/veth25c720b --prefix=/net/ipv6/conf/veth25c720b --prefix=/net/ipv6/neigh/veth25c720b\n12.867  rustc            308112 307990   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n12.890  rustc            308115 307929   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n12.894  systemd-sysctl   308114 308090   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth54fd746 --prefix=/net/ipv4/neigh/veth54fd746 --prefix=/net/ipv6/conf/veth54fd746 --prefix=/net/ipv6/neigh/veth54fd746\n12.910  rustc            308115 307929   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n12.910  systemd-sysctl   308124 308096   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethcce6eba --prefix=/net/ipv4/neigh/vethcce6eba --prefix=/net/ipv6/conf/vethcce6eba --prefix=/net/ipv6/neigh/vethcce6eba\n12.916  docker           308128 307929   0 /usr/bin/docker --help\n12.924  containerd-shim  308129 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 836afd09df38af279814304bcb25ac85197cd0f2303d44eea814005e67f49108 start\n12.930  containerd-shim  308143 308129   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 836afd09df38af279814304bcb25ac85197cd0f2303d44eea814005e67f49108 -address /var/run/docker/containerd/containerd.sock\n12.936  docker           308154 307929   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n12.936  systemd-sysctl   308150 308103   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb56ebd3 --prefix=/net/ipv4/neigh/vethb56ebd3 --prefix=/net/ipv6/conf/vethb56ebd3 --prefix=/net/ipv6/neigh/vethb56ebd3\n12.940  runc             308160 308143   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/836afd09df38af279814304bcb25ac85197cd0f2303d44eea814005e67f --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/836afd09df38af279814304bcb25ac85197cd0f2303d44eea814005e67f --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/836afd09df38af279814304bcb25ac85197cd0f2303d44eea814005e67f 836afd09df38af279814304bcb25ac85197cd0f2303d44eea814005e67f49108\n12.947  containerd-shim  308168 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 4cded3829f307ebca73b94acf8e628a85ee43617d7be54c2ee58bc6928b39863 start\n12.951  systemd-sysctl   308163 308111   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth60e54ed --prefix=/net/ipv4/neigh/veth60e54ed --prefix=/net/ipv6/conf/veth60e54ed --prefix=/net/ipv6/neigh/veth60e54ed\n12.951  containerd-shim  308174 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 872a26542e936ffdafc5a69457becb3dbc01d4b449698c8a2095198f3137cb52 start\n12.953  exe              308185 308160   0 /proc/self/exe init\n12.957  containerd-shim  308186 308168   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 4cded3829f307ebca73b94acf8e628a85ee43617d7be54c2ee58bc6928b39863 -address /var/run/docker/containerd/containerd.sock\n12.957  containerd-shim  308194 308174   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 872a26542e936ffdafc5a69457becb3dbc01d4b449698c8a2095198f3137cb52 -address /var/run/docker/containerd/containerd.sock\n12.959  runc             308201 1599     0 /usr/bin/runc --version\n12.961  runc             308207 308186   0 \n12.963  docker-init      308220 1599     0 /usr/bin/docker-init --version\n12.970  docker           308226 307929   0 /usr/bin/docker info -f {{.SecurityOptions}}\n12.970  runc             308221 308194   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/872a26542e936ffdafc5a69457becb3dbc01d4b449698c8a2095198f313 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/872a26542e936ffdafc5a69457becb3dbc01d4b449698c8a2095198f313 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/872a26542e936ffdafc5a69457becb3dbc01d4b449698c8a2095198f313 872a26542e936ffdafc5a69457becb3dbc01d4b449698c8a2095198f3137cb52\n12.972  exe              308237 308207   0 /proc/self/exe init\n12.974  exe              308240 308221   0 /proc/self/exe init\n12.988  runc             308246 1599     0 /usr/bin/runc --version\n12.995  docker-init      308251 1599     0 /usr/bin/docker-init --version\n13.035  rustup           308253 307929   0 /home/xmoe/.cargo/bin/rustup toolchain list\n13.048  rustup           308262 307929   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n13.104  rustup           308271 307929   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n13.157  uname            308296 307929   0 /usr/bin/uname -r\n13.172  exe              308297 308221   0 /proc/1599/exe -exec-root=/var/run/docker 872a26542e936ffdafc5a69457becb3dbc01d4b449698c8a2095198f3137cb52 d7da31e8f8e1\n13.173  exe              308303 308160   0 /proc/1599/exe -exec-root=/var/run/docker 836afd09df38af279814304bcb25ac85197cd0f2303d44eea814005e67f49108 d7da31e8f8e1\n13.187  docker           308315 307929   0 \n13.189  exe              308316 308207   0 /proc/1599/exe -exec-root=/var/run/docker 4cded3829f307ebca73b94acf8e628a85ee43617d7be54c2ee58bc6928b39863 d7da31e8f8e1\n13.218  exe              308332 1599     0 /proc/self/exe /var/run/docker/netns/d882d95735a1 all false\n13.221  exe              308333 1599     0 /proc/self/exe /var/run/docker/netns/bcc76f79eb62 all false\n13.239  exe              308355 1599     0 /proc/self/exe /var/run/docker/netns/e15e233e5f7a all false\n13.303  runc             308367 308194   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/872a26542e936ffdafc5a69457becb3dbc01d4b449698c8a2095198f313 --log-format json --systemd-cgroup start 872a26542e936ffdafc5a69457becb3dbc01d4b449698c8a2095198f3137cb52\n13.312  sh               308283 308194   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n13.313  cargo            308372 308283   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n13.329  runc             308374 308143   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/836afd09df38af279814304bcb25ac85197cd0f2303d44eea814005e67f --log-format json --systemd-cgroup start 836afd09df38af279814304bcb25ac85197cd0f2303d44eea814005e67f49108\n13.336  cargo-native-tr  308372 308283   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n13.340  sh               308281 308143   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n13.341  cargo            308380 308372   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n13.345  systemd-sysctl   308382 308090   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha8261a5 --prefix=/net/ipv4/neigh/vetha8261a5 --prefix=/net/ipv6/conf/vetha8261a5 --prefix=/net/ipv6/neigh/vetha8261a5\n13.345  systemd-sysctl   308381 308096   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth1bca9ba --prefix=/net/ipv4/neigh/veth1bca9ba --prefix=/net/ipv6/conf/veth1bca9ba --prefix=/net/ipv6/neigh/veth1bca9ba\n13.345  cargo            308383 308281   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n13.360  rustc            308384 308380   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.362  runc             308385 308186   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4cded3829f307ebca73b94acf8e628a85ee43617d7be54c2ee58bc6928b --log-format json --systemd-cgroup start 4cded3829f307ebca73b94acf8e628a85ee43617d7be54c2ee58bc6928b39863\n13.362  cargo-native-tr  308383 308281   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n13.363  containerd-shim  308387 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id ea774533e20c2670d973ced1c36fe3c313245886da95d5be3461c382fc7c3de4 start\n13.367  containerd-shim  308399 308387   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id ea774533e20c2670d973ced1c36fe3c313245886da95d5be3461c382fc7c3de4 -address /var/run/docker/containerd/containerd.sock\n13.367  cargo            308395 308383   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n13.374  runc             308410 308399   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ea774533e20c2670d973ced1c36fe3c313245886da95d5be3461c382fc7 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ea774533e20c2670d973ced1c36fe3c313245886da95d5be3461c382fc7 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ea774533e20c2670d973ced1c36fe3c313245886da95d5be3461c382fc7 ea774533e20c2670d973ced1c36fe3c313245886da95d5be3461c382fc7c3de4\n13.376  rustc            308411 308380   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n13.385  exe              308420 308410   0 /proc/self/exe init\n13.387  rustc            308421 308395   0 \n13.390  sh               308282 308186   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n13.393  cargo            308425 308282   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n13.404  rustc            308427 308395   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n13.410  execsnoop        308429 308372   0 /usr/local/bin/execsnoop -t\n13.412  cargo-native-tr  308425 308282   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n13.412  python3          308429 308372   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n13.416  cargo            308434 308425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n13.429  execsnoop        308442 308383   0 /usr/local/bin/execsnoop -t\n13.431  python3          308442 308383   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n13.448  rustc            308445 308434   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.449  as               308446 306553   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-index_builder.o /tmp/cce9Zwjk.s\n13.464  exe              308448 308410   0 /proc/1599/exe -exec-root=/var/run/docker ea774533e20c2670d973ced1c36fe3c313245886da95d5be3461c382fc7c3de4 d7da31e8f8e1\n13.471  rustc            308454 308434   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n13.503  execsnoop        308460 308425   0 /usr/local/bin/execsnoop -t\n13.503  python3          308460 308425   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n13.529  exe              308464 1599     0 /proc/self/exe /var/run/docker/netns/d3309d32733e all false\n13.614  runc             308475 308399   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ea774533e20c2670d973ced1c36fe3c313245886da95d5be3461c382fc7 --log-format json --systemd-cgroup start ea774533e20c2670d973ced1c36fe3c313245886da95d5be3461c382fc7c3de4\n13.626  sh               308436 308399   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n13.627  cargo            308481 308436   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n13.652  cargo-native-tr  308481 308436   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n13.654  cargo            308482 308481   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n13.675  rustc            308483 308482   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.695  rustc            308485 308482   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n13.707  as               308486 301592   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/8d9638b5dd27dacb-in_memory_stats_history.o /tmp/ccgvXm8b.s\n13.723  execsnoop        308490 308481   0 /usr/local/bin/execsnoop -t\n13.724  python3          308490 308481   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n14.452  powerpc64le-lin  308493 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n14.459  cc1plus          308494 308493   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n14.857  aarch64-linux-g  308495 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n14.863  cc1plus          308496 308495   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n14.869  as               308497 305117   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/8d9638b5dd27dacb-persistent_stats_history. /tmp/ccRfGwhJ.s\n15.477  powerpc64le-lin  308498 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n15.481  cc1plus          308499 308498   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n15.545  as               308500 307311   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-reader_common.o /tmp/ccE29BtB.s\n15.866  aarch64-linux-g  308502 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n15.871  cc1plus          308503 308502   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n16.469  runc             308505 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2065210498 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n16.477  exe              308513 308505   0 /proc/self/exe init\n16.504  as               308520 301458   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-block_based_table_factory.o /tmp/ccMxjdr1.s\n16.528  curl             308515 308505   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n16.642  as               308521 306784   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/053adb4869b9269c-block_cache.o /tmp/ccPFSDVj.s\n16.761  as               308522 306898   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-partitioned_filter_block.o /tmp/cc41Oqiq.s\n16.842  riscv64-linux-g  308523 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n16.847  cc1plus          308524 308523   0 \n17.103  as               308525 307506   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/053adb4869b9269c-parsed_full_filter_block.o /tmp/cc19ls1O.s\n17.135  as               308526 306557   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/94ad6eef41e52848-db_options.o /tmp/cch987RB.s\n17.144  cargo            308527 308383   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n17.157  cargo            308528 308425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n17.164  rustc            308529 308527   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.182  rustc            308533 308528   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.203  rustc            308536 308527   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pkg_config --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.33/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=4287493f147b149e ...\n17.222  rustc            308546 308528   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.139/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n17.224  rustc            308547 308528   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pkg_config --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.26/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=3b393852d2f0042a ...\n17.374  as               308559 307538   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/053adb4869b9269c-block_builder.o /tmp/cc4P5HfK.s\n17.375  aarch64-linux-g  308558 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n17.388  cc1plus          308560 308558   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n17.402  cc               308561 308546   0 /tmp/native-trace-308425-1783993842793/shims/cc -m64 /target/debug/build/libc-d5e24a35c6204c3a/rustciOulZw/symbols.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.0.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.1.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.f2zdzhd5zba24j4jlc52eo9qw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n17.414  cc               308562 308561   0 /usr/bin/cc -m64 /target/debug/build/libc-d5e24a35c6204c3a/rustciOulZw/symbols.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.0.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.1.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.f2zdzhd5zba24j4jlc52eo9qw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n17.418  collect2         308563 308562   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cceX9AIb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.426  ld.lld           308564 308563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cceX9AIb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a ...\n17.429  rust-lld         308564 308563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cceX9AIb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.454  riscv64-linux-g  308565 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n17.461  cc1plus          308566 308565   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n17.471  cargo            308583 308481   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n17.497  rustc            308586 308583   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.551  rustc            308596 308583   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pkg_config --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.33/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=4287493f147b149e ...\n17.572  build-script-bu  308602 308528   0 /target/debug/build/libc-d5e24a35c6204c3a/build-script-build\n17.575  rustc            308606 308602   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n17.596  rustc            308611 308528   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.139/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n17.653  cargo            308620 308372   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n17.676  rustc            308624 308620   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.709  rustc            308633 308620   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pkg_config --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.33/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=4287493f147b149e ...\n17.763  rustc            308640 308527   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"pkg-config\" --check-cfg cfg(docsrs,test) ...\n17.805  rustc            308645 308528   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"all\", \"dox\", \"dpms\", \"glx\", \"xcursor\", \"xf86vmode\", \"xfixes\", \"xft\", \"xinerama\", \"xinput\", \"xlib\", \"xlib_xc -C metadata=255bbe92912e964c ...\n17.867  cc               308667 308640   0 \n17.871  cc               308668 308667   0 /usr/bin/cc -m64 /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/rustc26zTyO/symbols.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.03sx8cpjf2ocjut57veg2bgs8.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.1w7a8mqkqkoq1y9i32ajvcgsf.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.3frbdn84inccfq2ljrasvkxov.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.46k5jenuyqpw08831gww4nysh.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.4kfnscuxrkmnv941he0qvdupv.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.6smau0y4fw6mq9vacn9k5ma0s.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.7864bt208ifxqgyti1gl1xfuk.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.7u2tpg0qgpx4wk3jppfk4tdzi.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.8rtl4hgzinygzde3cy5vs66py.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.c92o4p3xek8y97co3g7geiosf.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.d4hg4o1y9k5vtz47028d2m6pu.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.dqlqrbawxyeuuuhr15h7r37of.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.dxbd559uoc94qky1fji60pnnh.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.e8091drgsa8g8qwjo7nf0v7z8.0k2qxoc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libpkg_config-15486b590baf4edc.rlib ...\n17.875  collect2         308670 308668   0 \n17.882  rust-lld         308673 308670   0 \n17.882  ld.lld           308673 308670   0 \n17.886  as               308674 306804   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/94ad6eef41e52848-options.o /tmp/cccaAO5i.s\n17.952  cc               308715 308645   0 /tmp/native-trace-308425-1783993842793/shims/cc -m64 /target/debug/build/x11-5b80cb4da447746c/rustcUbVrK4/symbols.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.0qpi4mfmdotxvbce65x1xolh5.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.1y5yvu9jfka2c9w6hdajk52mn.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2pgg0dydoon132lopfe3oeztn.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2xh8j4d4a8yjbzwckhvntue0x.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.39j5lffqj7iy9ky93lf4m1dvl.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.3hkihxlli2q3axu4j61quupxj.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.44rz59wt54t9whocyj6tl3sy6.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.4yf6piehmld0y3l6zfsp08p38.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5afi2faxvl1q1vcdkgjl4nd14.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5vhsfxiiyspcnnavjjajlnp0z.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6apyjtfohf32ep2noq6qjeum7.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6iul0kjx749ugjo89pfuv6u0w.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7it1b9op5prid5fjylbt91g33.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7tq31ucs1ym2b1in8e7evpg2l.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8g3fir08766ptuc0avn1jc9o0.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8sze6dttyazzx1z68t3af3lec.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.9axw8cp9299kam4l1cekxkbkl.0u8jwqx.rcgu.o ...\n17.953  cc               308716 308715   0 /usr/bin/cc -m64 /target/debug/build/x11-5b80cb4da447746c/rustcUbVrK4/symbols.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.0qpi4mfmdotxvbce65x1xolh5.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.1y5yvu9jfka2c9w6hdajk52mn.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2pgg0dydoon132lopfe3oeztn.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2xh8j4d4a8yjbzwckhvntue0x.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.39j5lffqj7iy9ky93lf4m1dvl.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.3hkihxlli2q3axu4j61quupxj.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.44rz59wt54t9whocyj6tl3sy6.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.4yf6piehmld0y3l6zfsp08p38.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5afi2faxvl1q1vcdkgjl4nd14.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5vhsfxiiyspcnnavjjajlnp0z.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6apyjtfohf32ep2noq6qjeum7.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6iul0kjx749ugjo89pfuv6u0w.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7it1b9op5prid5fjylbt91g33.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7tq31ucs1ym2b1in8e7evpg2l.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8g3fir08766ptuc0avn1jc9o0.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8sze6dttyazzx1z68t3af3lec.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.9axw8cp9299kam4l1cekxkbkl.0u8jwqx.rcgu.o ...\n17.957  collect2         308717 308716   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYkPLvQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.964  ld.lld           308719 308717   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYkPLvQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c ...\n17.964  rust-lld         308719 308717   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYkPLvQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.010  build-script-bu  308740 308527   0 \n18.014  pkg-config       308743 308740   0 /tmp/native-trace-308383-1783993842743/shims/pkg-config --libs --cflags dbus-1 dbus-1 >= 1.6\n18.014  pkg-config       308744 308743   0 /usr/bin/pkg-config --libs --cflags dbus-1 dbus-1 >= 1.6\n18.031  sleep            308746 2147357   0 /usr/bin/sleep 180\n18.103  build-script-bu  308753 308528   0 /target/debug/build/x11-5b80cb4da447746c/build-script-build\n18.141  rustc            308757 308583   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"pkg-config\" --check-cfg cfg(docsrs,test) ...\n18.171  rustc            308765 308528   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name x11 --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"all\", \"dox\", \"dpms\", \"glx\", \"xcursor\", \"xf86vmode\", \"xfixes\", \"xft\", \"xinerama\", \"xinput\", \"xlib\", \"xlib_xc -C metadata=22d130f92e665544 ...\n18.238  cc               308788 308757   0 /tmp/native-trace-308481-1783993843030/shims/cc -m64 /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/rustcqe1756/symbols.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.03sx8cpjf2ocjut57veg2bgs8.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.1w7a8mqkqkoq1y9i32ajvcgsf.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.3frbdn84inccfq2ljrasvkxov.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.46k5jenuyqpw08831gww4nysh.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.4kfnscuxrkmnv941he0qvdupv.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.6smau0y4fw6mq9vacn9k5ma0s.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.7864bt208ifxqgyti1gl1xfuk.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.7u2tpg0qgpx4wk3jppfk4tdzi.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.8rtl4hgzinygzde3cy5vs66py.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.c92o4p3xek8y97co3g7geiosf.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.d4hg4o1y9k5vtz47028d2m6pu.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.dqlqrbawxyeuuuhr15h7r37of.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.dxbd559uoc94qky1fji60pnnh.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.e8091drgsa8g8qwjo7nf0v7z8.0luh8mn.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libpkg_config-15486b590baf4edc.rlib ...\n18.240  cc               308789 308788   0 /usr/bin/cc -m64 /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/rustcqe1756/symbols.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.03sx8cpjf2ocjut57veg2bgs8.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.1w7a8mqkqkoq1y9i32ajvcgsf.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.3frbdn84inccfq2ljrasvkxov.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.46k5jenuyqpw08831gww4nysh.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.4kfnscuxrkmnv941he0qvdupv.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.6smau0y4fw6mq9vacn9k5ma0s.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.7864bt208ifxqgyti1gl1xfuk.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.7u2tpg0qgpx4wk3jppfk4tdzi.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.8rtl4hgzinygzde3cy5vs66py.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.c92o4p3xek8y97co3g7geiosf.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.d4hg4o1y9k5vtz47028d2m6pu.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.dqlqrbawxyeuuuhr15h7r37of.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.dxbd559uoc94qky1fji60pnnh.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.e8091drgsa8g8qwjo7nf0v7z8.0luh8mn.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libpkg_config-15486b590baf4edc.rlib ...\n18.247  collect2         308790 308789   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccCle67m.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.250  ld.lld           308791 308790   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccCle67m.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9 ...\n18.255  rust-lld         308791 308790   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccCle67m.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.255  rustc            308793 308620   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"pkg-config\" --check-cfg cfg(docsrs,test) ...\n18.337  powerpc64le-lin  308813 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n18.347  powerpc64le-lin  308814 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n18.349  cc1plus          308815 308813   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n18.350  cc1plus          308816 308814   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n18.392  build-script-bu  308831 308583   0 /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build-script-build\n18.394  pkg-config       308834 308831   0 /tmp/native-trace-308481-1783993843030/shims/pkg-config --libs --cflags dbus-1 dbus-1 >= 1.6\n18.395  pkg-config       308835 308834   0 /usr/bin/pkg-config --libs --cflags dbus-1 dbus-1 >= 1.6\n18.407  cc               308836 308793   0 /tmp/native-trace-308372-1783993842718/shims/cc -m64 /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/rustc6lq0oZ/symbols.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.03sx8cpjf2ocjut57veg2bgs8.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.1w7a8mqkqkoq1y9i32ajvcgsf.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.3frbdn84inccfq2ljrasvkxov.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.46k5jenuyqpw08831gww4nysh.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.4kfnscuxrkmnv941he0qvdupv.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.6smau0y4fw6mq9vacn9k5ma0s.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.7864bt208ifxqgyti1gl1xfuk.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.7u2tpg0qgpx4wk3jppfk4tdzi.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.8rtl4hgzinygzde3cy5vs66py.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.c92o4p3xek8y97co3g7geiosf.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.d4hg4o1y9k5vtz47028d2m6pu.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.dqlqrbawxyeuuuhr15h7r37of.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.dxbd559uoc94qky1fji60pnnh.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.e8091drgsa8g8qwjo7nf0v7z8.04b5br9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libpkg_config-15486b590baf4edc.rlib ...\n18.409  cc               308837 308836   0 \n18.417  collect2         308838 308837   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc5CCs4n.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.420  ld.lld           308839 308838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc5CCs4n.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9 ...\n18.421  rust-lld         308839 308838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc5CCs4n.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.599  build-script-bu  308857 308620   0 /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build-script-build\n18.601  pkg-config       308858 308857   0 /tmp/native-trace-308372-1783993842718/shims/pkg-config --libs --cflags dbus-1 dbus-1 >= 1.6\n18.603  pkg-config       308859 308858   0 /usr/bin/pkg-config --libs --cflags dbus-1 dbus-1 >= 1.6\n18.666  powerpc64le-lin  308860 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n18.669  cc1plus          308861 308860   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n18.736  runc             308862 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process2230170049 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n18.750  exe              308870 308862   0 /proc/self/exe init\n18.768  curl             308872 308862   0 /usr/bin/curl -f http://localhost:9091/healthz\n19.027  as               308879 307220   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/a357d10ea739bc2c-adaptive_table_factory.o /tmp/cc8YI2WH.s\n19.106  as               308880 301477   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/9b96b3b3b98b387b-write_buffer_manager.o /tmp/ccrLGkMr.s\n19.167  as               308881 306196   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-filter_policy.o /tmp/ccgmoz0g.s\n19.197  runc             308882 306331   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/785f2834218e0c5aa85c3f869434afca5f72bbb169e4e1db517f0943746 --log-format json --systemd-cgroup kill --all 785f2834218e0c5aa85c3f869434afca5f72bbb169e4e1db517f094374635af3 9\n19.228  runc             308888 306331   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/785f2834218e0c5aa85c3f869434afca5f72bbb169e4e1db517f0943746 --log-format json --systemd-cgroup delete 785f2834218e0c5aa85c3f869434afca5f72bbb169e4e1db517f094374635af3\n19.275  powerpc64le-lin  308894 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n19.284  cc1plus          308895 308894   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n19.472  containerd-shim  308901 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 785f2834218e0c5aa85c3f869434afca5f72bbb169e4e1db517f094374635af3 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/785f2834218e0c5aa85c3f869434afca5f72bbb169e4e1db517f0943746 delete\n19.478  runc             308909 308901   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/785f2834218e0c5aa85c3f869434afca5f72bbb169e4e1db517f094374635af --log-format json delete --force 785f2834218e0c5aa85c3f869434afca5f72bbb169e4e1db517f094374635af3\n19.553  systemd-sysctl   308939 308938   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc657b59 --prefix=/net/ipv4/neigh/vethc657b59 --prefix=/net/ipv6/conf/vethc657b59 --prefix=/net/ipv6/neigh/vethc657b59\n19.595  as               308941 307483   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/053adb4869b9269c-full_filter_block.o /tmp/cc5hrJN4.s\n"
}
```

#### Record 25

```json
{
  "argv": [
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 306978,
  "build_script_target_dir": "io-uring-ea6b6ff132ca8689",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build",
  "pid": 306978,
  "ppid": 306862,
  "root_cargo_pid": 306862,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "_build_script_out_dir": "/target/debug/build/io-uring-ea6b6ff132ca8689/out"
}
```

#### Record 26

```json
{
  "argv": [
    "/target/debug/build/libc-1f865bb516326eef/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 307012,
  "build_script_target_dir": "libc-1f865bb516326eef",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/libc-1f865bb516326eef/build-script-build",
  "pid": 307012,
  "ppid": 306862,
  "root_cargo_pid": 306862,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "libc",
    "version": "0.2.156",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
  "_build_script_out_dir": "/target/debug/build/libc-1f865bb516326eef/out"
}
```

#### Record 27

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 307012,
  "build_script_target_dir": "libc-1f865bb516326eef",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 307013,
  "ppid": 307012,
  "root_cargo_pid": 306862,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "libc",
    "version": "0.2.156",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
  "_build_script_out_dir": "/target/debug/build/libc-1f865bb516326eef/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 28

```json
{
  "crate": "io-uring",
  "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "event_id": "bsrun:7203d1786fb49915:7834fb0e631a74d9:c734c2099efb859a",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
  "out_dir": "/target/debug/build/io-uring-ea6b6ff132ca8689/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
  "success": true,
  "target": null,
  "version": "0.7.9",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
    "source": "cwd_prefix"
  }
}
```

#### Record 29

```json
{
  "crate": "libc",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
  "event_id": "bsrun:3a1186cd8cfe6ec2:851b2d1179e7fd28:6fc17f8c88bab7fd",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/libc-1f865bb516326eef/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
  "out_dir": "/target/debug/build/libc-1f865bb516326eef/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
  "success": true,
  "target": null,
  "version": "0.2.156",
  "_owner": {
    "crate": "libc",
    "version": "0.2.156",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
    "source": "cwd_prefix"
  }
}
```

#### Record 30

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 307012,
  "build_script_target_dir": "libc-1f865bb516326eef",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 307013,
  "ppid": 307012,
  "root_cargo_pid": 306862,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T01:50:54.423366+00:00",
  "crate": "io-uring",
  "version": "0.7.9",
  "architecture": "ppc64le",
  "duration_seconds": 34.268128633033484,
  "trace_record_count": 29,
  "trace_owner_summary": {
    "owner_package_count": 18,
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
        "crate": "windows-sys",
        "version": "0.52.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.52.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.52.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.52.0/Cargo.toml"
      },
      {
        "crate": "bitflags",
        "version": "2.6.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.6.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.6.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.6.0/Cargo.toml"
      },
      {
        "crate": "anyhow",
        "version": "1.0.86",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#anyhow@1.0.86",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anyhow-1.0.86",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anyhow-1.0.86/Cargo.toml"
      },
      {
        "crate": "autocfg",
        "version": "1.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.3.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.3.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.3.0/Cargo.toml"
      },
      {
        "crate": "socket2",
        "version": "0.5.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#socket2@0.5.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/socket2-0.5.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/socket2-0.5.7/Cargo.toml"
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
        "version": "0.2.156",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156/Cargo.toml"
      },
      {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#slab@0.4.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.9/Cargo.toml"
      },
      {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
        "manifest_path": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9/Cargo.toml"
      }
    ],
    "attributed_event_count": 24,
    "unattributed_event_count": 5,
    "owners": [
      {
        "crate": "io-uring",
        "version": "0.7.9",
        "event_count": 14,
        "kind_counts": {
          "native_trace_root_context": 1,
          "exec": 1,
          "used_input": 8,
          "link": 1,
          "exec_context": 1,
          "resolved_link": 1,
          "build_script_run": 1
        }
      },
      {
        "crate": "libc",
        "version": "0.2.156",
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
      "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "workspace_root": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#anyhow@1.0.86",
          "name": "anyhow",
          "version": "1.0.86",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anyhow-1.0.86/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anyhow-1.0.86"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.3.0",
          "name": "autocfg",
          "version": "1.3.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.3.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.6.0",
          "name": "bitflags",
          "version": "2.6.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.6.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.6.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
          "name": "cfg-if",
          "version": "1.0.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0"
        },
        {
          "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
          "name": "io-uring",
          "version": "0.7.9",
          "manifest_path": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
          "name": "libc",
          "version": "0.2.156",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#slab@0.4.9",
          "name": "slab",
          "version": "0.4.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#socket2@0.5.7",
          "name": "socket2",
          "version": "0.5.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/socket2-0.5.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/socket2-0.5.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.52.0",
          "name": "windows-sys",
          "version": "0.52.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.52.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.52.0"
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
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "exit_code": 0,
      "kind": "exec",
      "pid": 306953,
      "ppid": 306888,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "io-uring",
      "cargo_pkg_version": "0.7.9",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "event_id": "used:cc:68232c9559a91bb5:3aa7eaa3b713ccc3:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
      "pid": 306953,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "io-uring",
      "cargo_pkg_version": "0.7.9",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "event_id": "used:cc:68232c9559a91bb5:53efe489880addb5:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
      "pid": 306953,
      "sha256": "bf6b59b4e3c99abaabb968b8ef4de0cf27f9d51afe5a1aee8826ffa0f36ba95f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "io-uring",
      "cargo_pkg_version": "0.7.9",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "event_id": "used:cc:68232c9559a91bb5:5dc6ddddfc7207e5:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
      "pid": 306953,
      "sha256": "73b560f9d258462e97ac0b121ece6387528181283743c662f8a5a32e8fe54970",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "io-uring",
      "cargo_pkg_version": "0.7.9",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "event_id": "used:cc:68232c9559a91bb5:80bf3885172142d7:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
      "pid": 306953,
      "sha256": "8e60849e2e1fa2882bdce1af13785c26e41dbc0a8236fe03f0b50bcdd3a797ae",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "io-uring",
      "cargo_pkg_version": "0.7.9",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "event_id": "used:cc:68232c9559a91bb5:5ad62714990aca26:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
      "pid": 306953,
      "sha256": "1c2d8c3bee2c30f913a81ac55ee66f7a17e8baa63f1dee6910366cef396628b9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "io-uring",
      "cargo_pkg_version": "0.7.9",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "event_id": "used:cc:68232c9559a91bb5:e41b13ee82538241:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
      "pid": 306953,
      "sha256": "833bd7df179cc96ce4c36692b7cc587abbc4c6ec31c49e00b71a7f1b0d21d769",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "io-uring",
      "cargo_pkg_version": "0.7.9",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "event_id": "used:cc:68232c9559a91bb5:d5de41d760e2f9f7:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
      "pid": 306953,
      "sha256": "bae7432832fe963def547d3943c9d93a0232bf96a891e44d192fc8b34ab39896",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "io-uring",
      "cargo_pkg_version": "0.7.9",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "event_id": "used:cc:68232c9559a91bb5:18397aba03f9d7bc:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
      "pid": 306953,
      "sha256": "19fb2eeea9364d7061347a67eb332563a7bbc8fc2340cd95e11b69ef53605881",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
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
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "cargo_pkg_name": "io-uring",
      "cargo_pkg_version": "0.7.9",
      "context_path": "/tmp/native-trace-306534-1783993825592/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-306534-1783993825592/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 306953,
      "ppid": 306888,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu",
        "/target/debug/build/io-uring-ea6b6ff132ca8689",
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
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-306953-1783993829801347974.map",
      "pid": 306953,
      "ppid": 306888,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-306953-1783993829801347974.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
      "exit_code": 0,
      "kind": "exec",
      "pid": 306987,
      "ppid": 306881,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.156",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.156",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
      "event_id": "used:cc:bf4e8db12c663bbd:841a833fb42f1ec0:c338943aef9d968a",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
      "path": "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
      "pid": 306987,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.156",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.156",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
      "event_id": "used:cc:bf4e8db12c663bbd:c351fdf3b90cd87c:c338943aef9d968a",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
      "path": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
      "pid": 306987,
      "sha256": "cbff5439c75a325335168109f20812815f73bb83aa61b6a39fc0e85c9630736f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.156",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.156",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
      "event_id": "used:cc:bf4e8db12c663bbd:f5df9fdcfd49e411:c338943aef9d968a",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
      "path": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
      "pid": 306987,
      "sha256": "74114b97c4c1a2a2fdaa1fa79131ee09c3ef2cf13f76d162a3dc6f8ae200ba31",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.156",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.156",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
      "event_id": "used:cc:bf4e8db12c663bbd:606c2cc26e257c19:c338943aef9d968a",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
      "path": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
      "pid": 306987,
      "sha256": "c692600706608b1e9eabffd7d767acfc1d3c6acbe697570721bc0134a564ed00",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.156",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.156",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
      "event_id": "used:cc:bf4e8db12c663bbd:c3f5f7670c879a45:c338943aef9d968a",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
      "path": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
      "pid": 306987,
      "sha256": "36ecc7e54d00c83fc17a4733a461ba67af8a95446b620a081829593ce43b942f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.156",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/raw-dylibs",
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
      "output": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.156",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.156",
      "context_path": "/tmp/native-trace-306534-1783993825592/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-306534-1783993825592/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 306987,
      "ppid": 306881,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "_owner": {
        "crate": "libc",
        "version": "0.2.156",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN",
        "/target/debug/build/libc-1f865bb516326eef",
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
          "directory": "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN",
          "kind": "object",
          "path": "/target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-1f865bb516326eef",
          "kind": "object",
          "path": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-1f865bb516326eef",
          "kind": "object",
          "path": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-1f865bb516326eef",
          "kind": "object",
          "path": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-1f865bb516326eef",
          "kind": "object",
          "path": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-306987-1783993830001112262.map",
      "pid": 306987,
      "ppid": 306881,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-306987-1783993830001112262.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "libc",
        "version": "0.2.156",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
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
      "parsed_event_count": 480,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 481,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "/rustc --print sysroot\n12.406  docker-init      307797 1599     0 /usr/bin/docker-init --version\n12.411  docker           307811 307618   0 /usr/bin/docker info -f {{.SecurityOptions}}\n12.415  rustc            307796 307664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n12.415  rustc            307795 307727   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n12.441  runc             307830 1599     0 /usr/bin/runc --version\n12.441  docker           307832 307727   0 /usr/bin/docker --help\n12.441  docker           307831 307664   0 /usr/bin/docker --help\n12.448  docker-init      307848 1599     0 /usr/bin/docker-init --version\n12.464  docker           307854 307727   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n12.476  docker           307861 307664   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n12.491  runc             307874 1599     0 /usr/bin/runc --version\n12.499  runc             307879 1599     0 /usr/bin/runc --version\n12.504  docker-init      307885 1599     0 /usr/bin/docker-init --version\n12.507  docker-init      307887 1599     0 \n12.507  docker           307886 307664   0 /usr/bin/docker info -f {{.SecurityOptions}}\n12.512  docker           307893 307727   0 /usr/bin/docker info -f {{.SecurityOptions}}\n12.515  rustup           307895 307618   0 /home/xmoe/.cargo/bin/rustup toolchain list\n12.525  rustup           307910 307618   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n12.525  runc             307911 1599     0 /usr/bin/runc --version\n12.530  docker-init      307925 1599     0 /usr/bin/docker-init --version\n12.562  cross            307929 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n12.563  rustc            307932 307929   0 /home/xmoe/.cargo/bin/rustc --print target-list\n12.565  rustup           307933 307618   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n12.567  rustup           307939 307664   0 /home/xmoe/.cargo/bin/rustup toolchain list\n12.569  runc             307946 1599     0 /usr/bin/runc --version\n12.572  rustc            307932 307929   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n12.576  rustup           307963 307664   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n12.590  rustc            307978 307929   0 /home/xmoe/.cargo/bin/rustc -vV\n12.598  rustc            307978 307929   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n12.605  docker-init      307987 1599     0 /usr/bin/docker-init --version\n12.605  uname            307988 307618   0 /usr/bin/uname -r\n12.616  rustup           307991 307664   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n12.616  cargo            307990 307929   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n12.641  cargo            307990 307929   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n12.641  docker           308008 307618   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n12.655  rustc            308017 307990   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n12.657  uname            308018 307664   0 /usr/bin/uname -r\n12.660  rustup           308019 307727   0 /home/xmoe/.cargo/bin/rustup toolchain list\n12.669  rustup           308031 307727   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n12.672  rustc            308032 307990   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n12.724  docker           308044 307664   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n12.737  rustup           308046 307727   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n12.737  rustc            308050 307990   0 \n12.774  uname            308067 307727   0 /usr/bin/uname -r\n12.802  docker           308068 307727   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n12.830  systemd-sysctl   308081 307553   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethbf5d69b --prefix=/net/ipv4/neigh/vethbf5d69b --prefix=/net/ipv6/conf/vethbf5d69b --prefix=/net/ipv6/neigh/vethbf5d69b\n12.830  systemd-sysctl   308082 307602   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth25c720b --prefix=/net/ipv4/neigh/veth25c720b --prefix=/net/ipv6/conf/veth25c720b --prefix=/net/ipv6/neigh/veth25c720b\n12.867  rustc            308112 307990   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n12.890  rustc            308115 307929   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n12.894  systemd-sysctl   308114 308090   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth54fd746 --prefix=/net/ipv4/neigh/veth54fd746 --prefix=/net/ipv6/conf/veth54fd746 --prefix=/net/ipv6/neigh/veth54fd746\n12.910  rustc            308115 307929   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n12.910  systemd-sysctl   308124 308096   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethcce6eba --prefix=/net/ipv4/neigh/vethcce6eba --prefix=/net/ipv6/conf/vethcce6eba --prefix=/net/ipv6/neigh/vethcce6eba\n12.916  docker           308128 307929   0 /usr/bin/docker --help\n12.924  containerd-shim  308129 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 836afd09df38af279814304bcb25ac85197cd0f2303d44eea814005e67f49108 start\n12.930  containerd-shim  308143 308129   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 836afd09df38af279814304bcb25ac85197cd0f2303d44eea814005e67f49108 -address /var/run/docker/containerd/containerd.sock\n12.936  docker           308154 307929   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n12.936  systemd-sysctl   308150 308103   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb56ebd3 --prefix=/net/ipv4/neigh/vethb56ebd3 --prefix=/net/ipv6/conf/vethb56ebd3 --prefix=/net/ipv6/neigh/vethb56ebd3\n12.940  runc             308160 308143   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/836afd09df38af279814304bcb25ac85197cd0f2303d44eea814005e67f --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/836afd09df38af279814304bcb25ac85197cd0f2303d44eea814005e67f --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/836afd09df38af279814304bcb25ac85197cd0f2303d44eea814005e67f 836afd09df38af279814304bcb25ac85197cd0f2303d44eea814005e67f49108\n12.947  containerd-shim  308168 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 4cded3829f307ebca73b94acf8e628a85ee43617d7be54c2ee58bc6928b39863 start\n12.951  systemd-sysctl   308163 308111   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth60e54ed --prefix=/net/ipv4/neigh/veth60e54ed --prefix=/net/ipv6/conf/veth60e54ed --prefix=/net/ipv6/neigh/veth60e54ed\n12.951  containerd-shim  308174 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 872a26542e936ffdafc5a69457becb3dbc01d4b449698c8a2095198f3137cb52 start\n12.953  exe              308185 308160   0 /proc/self/exe init\n12.957  containerd-shim  308186 308168   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 4cded3829f307ebca73b94acf8e628a85ee43617d7be54c2ee58bc6928b39863 -address /var/run/docker/containerd/containerd.sock\n12.957  containerd-shim  308194 308174   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 872a26542e936ffdafc5a69457becb3dbc01d4b449698c8a2095198f3137cb52 -address /var/run/docker/containerd/containerd.sock\n12.959  runc             308201 1599     0 /usr/bin/runc --version\n12.961  runc             308207 308186   0 \n12.963  docker-init      308220 1599     0 /usr/bin/docker-init --version\n12.970  docker           308226 307929   0 /usr/bin/docker info -f {{.SecurityOptions}}\n12.970  runc             308221 308194   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/872a26542e936ffdafc5a69457becb3dbc01d4b449698c8a2095198f313 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/872a26542e936ffdafc5a69457becb3dbc01d4b449698c8a2095198f313 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/872a26542e936ffdafc5a69457becb3dbc01d4b449698c8a2095198f313 872a26542e936ffdafc5a69457becb3dbc01d4b449698c8a2095198f3137cb52\n12.972  exe              308237 308207   0 /proc/self/exe init\n12.974  exe              308240 308221   0 /proc/self/exe init\n12.988  runc             308246 1599     0 /usr/bin/runc --version\n12.995  docker-init      308251 1599     0 /usr/bin/docker-init --version\n13.035  rustup           308253 307929   0 /home/xmoe/.cargo/bin/rustup toolchain list\n13.048  rustup           308262 307929   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n13.104  rustup           308271 307929   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n13.157  uname            308296 307929   0 /usr/bin/uname -r\n13.172  exe              308297 308221   0 /proc/1599/exe -exec-root=/var/run/docker 872a26542e936ffdafc5a69457becb3dbc01d4b449698c8a2095198f3137cb52 d7da31e8f8e1\n13.173  exe              308303 308160   0 /proc/1599/exe -exec-root=/var/run/docker 836afd09df38af279814304bcb25ac85197cd0f2303d44eea814005e67f49108 d7da31e8f8e1\n13.187  docker           308315 307929   0 \n13.189  exe              308316 308207   0 /proc/1599/exe -exec-root=/var/run/docker 4cded3829f307ebca73b94acf8e628a85ee43617d7be54c2ee58bc6928b39863 d7da31e8f8e1\n13.218  exe              308332 1599     0 /proc/self/exe /var/run/docker/netns/d882d95735a1 all false\n13.221  exe              308333 1599     0 /proc/self/exe /var/run/docker/netns/bcc76f79eb62 all false\n13.239  exe              308355 1599     0 /proc/self/exe /var/run/docker/netns/e15e233e5f7a all false\n13.303  runc             308367 308194   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/872a26542e936ffdafc5a69457becb3dbc01d4b449698c8a2095198f313 --log-format json --systemd-cgroup start 872a26542e936ffdafc5a69457becb3dbc01d4b449698c8a2095198f3137cb52\n13.312  sh               308283 308194   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n13.313  cargo            308372 308283   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n13.329  runc             308374 308143   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/836afd09df38af279814304bcb25ac85197cd0f2303d44eea814005e67f --log-format json --systemd-cgroup start 836afd09df38af279814304bcb25ac85197cd0f2303d44eea814005e67f49108\n13.336  cargo-native-tr  308372 308283   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n13.340  sh               308281 308143   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n13.341  cargo            308380 308372   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n13.345  systemd-sysctl   308382 308090   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha8261a5 --prefix=/net/ipv4/neigh/vetha8261a5 --prefix=/net/ipv6/conf/vetha8261a5 --prefix=/net/ipv6/neigh/vetha8261a5\n13.345  systemd-sysctl   308381 308096   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth1bca9ba --prefix=/net/ipv4/neigh/veth1bca9ba --prefix=/net/ipv6/conf/veth1bca9ba --prefix=/net/ipv6/neigh/veth1bca9ba\n13.345  cargo            308383 308281   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n13.360  rustc            308384 308380   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.362  runc             308385 308186   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4cded3829f307ebca73b94acf8e628a85ee43617d7be54c2ee58bc6928b --log-format json --systemd-cgroup start 4cded3829f307ebca73b94acf8e628a85ee43617d7be54c2ee58bc6928b39863\n13.362  cargo-native-tr  308383 308281   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n13.363  containerd-shim  308387 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id ea774533e20c2670d973ced1c36fe3c313245886da95d5be3461c382fc7c3de4 start\n13.367  containerd-shim  308399 308387   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id ea774533e20c2670d973ced1c36fe3c313245886da95d5be3461c382fc7c3de4 -address /var/run/docker/containerd/containerd.sock\n13.367  cargo            308395 308383   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n13.374  runc             308410 308399   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ea774533e20c2670d973ced1c36fe3c313245886da95d5be3461c382fc7 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ea774533e20c2670d973ced1c36fe3c313245886da95d5be3461c382fc7 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ea774533e20c2670d973ced1c36fe3c313245886da95d5be3461c382fc7 ea774533e20c2670d973ced1c36fe3c313245886da95d5be3461c382fc7c3de4\n13.376  rustc            308411 308380   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n13.385  exe              308420 308410   0 /proc/self/exe init\n13.387  rustc            308421 308395   0 \n13.390  sh               308282 308186   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n13.393  cargo            308425 308282   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n13.404  rustc            308427 308395   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n13.410  execsnoop        308429 308372   0 /usr/local/bin/execsnoop -t\n13.412  cargo-native-tr  308425 308282   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n13.412  python3          308429 308372   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n13.416  cargo            308434 308425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n13.429  execsnoop        308442 308383   0 /usr/local/bin/execsnoop -t\n13.431  python3          308442 308383   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n13.448  rustc            308445 308434   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.449  as               308446 306553   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-index_builder.o /tmp/cce9Zwjk.s\n13.464  exe              308448 308410   0 /proc/1599/exe -exec-root=/var/run/docker ea774533e20c2670d973ced1c36fe3c313245886da95d5be3461c382fc7c3de4 d7da31e8f8e1\n13.471  rustc            308454 308434   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n13.503  execsnoop        308460 308425   0 /usr/local/bin/execsnoop -t\n13.503  python3          308460 308425   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n13.529  exe              308464 1599     0 /proc/self/exe /var/run/docker/netns/d3309d32733e all false\n13.614  runc             308475 308399   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ea774533e20c2670d973ced1c36fe3c313245886da95d5be3461c382fc7 --log-format json --systemd-cgroup start ea774533e20c2670d973ced1c36fe3c313245886da95d5be3461c382fc7c3de4\n13.626  sh               308436 308399   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n13.627  cargo            308481 308436   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n13.652  cargo-native-tr  308481 308436   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n13.654  cargo            308482 308481   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n13.675  rustc            308483 308482   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.695  rustc            308485 308482   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n13.707  as               308486 301592   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/8d9638b5dd27dacb-in_memory_stats_history.o /tmp/ccgvXm8b.s\n13.723  execsnoop        308490 308481   0 /usr/local/bin/execsnoop -t\n13.724  python3          308490 308481   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n14.452  powerpc64le-lin  308493 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n14.459  cc1plus          308494 308493   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n14.857  aarch64-linux-g  308495 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n14.863  cc1plus          308496 308495   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n14.869  as               308497 305117   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/8d9638b5dd27dacb-persistent_stats_history. /tmp/ccRfGwhJ.s\n15.477  powerpc64le-lin  308498 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n15.481  cc1plus          308499 308498   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n15.545  as               308500 307311   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-reader_common.o /tmp/ccE29BtB.s\n15.866  aarch64-linux-g  308502 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n15.871  cc1plus          308503 308502   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n16.469  runc             308505 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2065210498 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n16.477  exe              308513 308505   0 /proc/self/exe init\n16.504  as               308520 301458   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-block_based_table_factory.o /tmp/ccMxjdr1.s\n16.528  curl             308515 308505   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n16.642  as               308521 306784   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/053adb4869b9269c-block_cache.o /tmp/ccPFSDVj.s\n16.761  as               308522 306898   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-partitioned_filter_block.o /tmp/cc41Oqiq.s\n16.842  riscv64-linux-g  308523 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n16.847  cc1plus          308524 308523   0 \n17.103  as               308525 307506   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/053adb4869b9269c-parsed_full_filter_block.o /tmp/cc19ls1O.s\n17.135  as               308526 306557   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/94ad6eef41e52848-db_options.o /tmp/cch987RB.s\n17.144  cargo            308527 308383   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n17.157  cargo            308528 308425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n17.164  rustc            308529 308527   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.182  rustc            308533 308528   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.203  rustc            308536 308527   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pkg_config --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.33/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=4287493f147b149e ...\n17.222  rustc            308546 308528   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.139/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n17.224  rustc            308547 308528   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pkg_config --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.26/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=3b393852d2f0042a ...\n17.374  as               308559 307538   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/053adb4869b9269c-block_builder.o /tmp/cc4P5HfK.s\n17.375  aarch64-linux-g  308558 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n17.388  cc1plus          308560 308558   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n17.402  cc               308561 308546   0 /tmp/native-trace-308425-1783993842793/shims/cc -m64 /target/debug/build/libc-d5e24a35c6204c3a/rustciOulZw/symbols.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.0.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.1.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.f2zdzhd5zba24j4jlc52eo9qw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n17.414  cc               308562 308561   0 /usr/bin/cc -m64 /target/debug/build/libc-d5e24a35c6204c3a/rustciOulZw/symbols.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.0.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.1.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.f2zdzhd5zba24j4jlc52eo9qw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n17.418  collect2         308563 308562   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cceX9AIb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.426  ld.lld           308564 308563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cceX9AIb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a ...\n17.429  rust-lld         308564 308563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cceX9AIb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.454  riscv64-linux-g  308565 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n17.461  cc1plus          308566 308565   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n17.471  cargo            308583 308481   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n17.497  rustc            308586 308583   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.551  rustc            308596 308583   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pkg_config --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.33/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=4287493f147b149e ...\n17.572  build-script-bu  308602 308528   0 /target/debug/build/libc-d5e24a35c6204c3a/build-script-build\n17.575  rustc            308606 308602   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n17.596  rustc            308611 308528   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.139/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n17.653  cargo            308620 308372   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n17.676  rustc            308624 308620   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.709  rustc            308633 308620   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pkg_config --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.33/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=4287493f147b149e ...\n17.763  rustc            308640 308527   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"pkg-config\" --check-cfg cfg(docsrs,test) ...\n17.805  rustc            308645 308528   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"all\", \"dox\", \"dpms\", \"glx\", \"xcursor\", \"xf86vmode\", \"xfixes\", \"xft\", \"xinerama\", \"xinput\", \"xlib\", \"xlib_xc -C metadata=255bbe92912e964c ...\n17.867  cc               308667 308640   0 \n17.871  cc               308668 308667   0 /usr/bin/cc -m64 /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/rustc26zTyO/symbols.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.03sx8cpjf2ocjut57veg2bgs8.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.1w7a8mqkqkoq1y9i32ajvcgsf.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.3frbdn84inccfq2ljrasvkxov.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.46k5jenuyqpw08831gww4nysh.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.4kfnscuxrkmnv941he0qvdupv.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.6smau0y4fw6mq9vacn9k5ma0s.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.7864bt208ifxqgyti1gl1xfuk.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.7u2tpg0qgpx4wk3jppfk4tdzi.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.8rtl4hgzinygzde3cy5vs66py.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.c92o4p3xek8y97co3g7geiosf.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.d4hg4o1y9k5vtz47028d2m6pu.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.dqlqrbawxyeuuuhr15h7r37of.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.dxbd559uoc94qky1fji60pnnh.0k2qxoc.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.e8091drgsa8g8qwjo7nf0v7z8.0k2qxoc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libpkg_config-15486b590baf4edc.rlib ...\n17.875  collect2         308670 308668   0 \n17.882  rust-lld         308673 308670   0 \n17.882  ld.lld           308673 308670   0 \n17.886  as               308674 306804   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/94ad6eef41e52848-options.o /tmp/cccaAO5i.s\n17.952  cc               308715 308645   0 /tmp/native-trace-308425-1783993842793/shims/cc -m64 /target/debug/build/x11-5b80cb4da447746c/rustcUbVrK4/symbols.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.0qpi4mfmdotxvbce65x1xolh5.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.1y5yvu9jfka2c9w6hdajk52mn.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2pgg0dydoon132lopfe3oeztn.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2xh8j4d4a8yjbzwckhvntue0x.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.39j5lffqj7iy9ky93lf4m1dvl.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.3hkihxlli2q3axu4j61quupxj.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.44rz59wt54t9whocyj6tl3sy6.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.4yf6piehmld0y3l6zfsp08p38.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5afi2faxvl1q1vcdkgjl4nd14.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5vhsfxiiyspcnnavjjajlnp0z.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6apyjtfohf32ep2noq6qjeum7.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6iul0kjx749ugjo89pfuv6u0w.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7it1b9op5prid5fjylbt91g33.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7tq31ucs1ym2b1in8e7evpg2l.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8g3fir08766ptuc0avn1jc9o0.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8sze6dttyazzx1z68t3af3lec.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.9axw8cp9299kam4l1cekxkbkl.0u8jwqx.rcgu.o ...\n17.953  cc               308716 308715   0 /usr/bin/cc -m64 /target/debug/build/x11-5b80cb4da447746c/rustcUbVrK4/symbols.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.0qpi4mfmdotxvbce65x1xolh5.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.1y5yvu9jfka2c9w6hdajk52mn.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2pgg0dydoon132lopfe3oeztn.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2xh8j4d4a8yjbzwckhvntue0x.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.39j5lffqj7iy9ky93lf4m1dvl.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.3hkihxlli2q3axu4j61quupxj.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.44rz59wt54t9whocyj6tl3sy6.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.4yf6piehmld0y3l6zfsp08p38.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5afi2faxvl1q1vcdkgjl4nd14.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5vhsfxiiyspcnnavjjajlnp0z.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6apyjtfohf32ep2noq6qjeum7.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6iul0kjx749ugjo89pfuv6u0w.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7it1b9op5prid5fjylbt91g33.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7tq31ucs1ym2b1in8e7evpg2l.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8g3fir08766ptuc0avn1jc9o0.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8sze6dttyazzx1z68t3af3lec.0u8jwqx.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.9axw8cp9299kam4l1cekxkbkl.0u8jwqx.rcgu.o ...\n17.957  collect2         308717 308716   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYkPLvQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.964  ld.lld           308719 308717   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYkPLvQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c ...\n17.964  rust-lld         308719 308717   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYkPLvQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.010  build-script-bu  308740 308527   0 \n18.014  pkg-config       308743 308740   0 /tmp/native-trace-308383-1783993842743/shims/pkg-config --libs --cflags dbus-1 dbus-1 >= 1.6\n18.014  pkg-config       308744 308743   0 /usr/bin/pkg-config --libs --cflags dbus-1 dbus-1 >= 1.6\n18.031  sleep            308746 2147357   0 /usr/bin/sleep 180\n18.103  build-script-bu  308753 308528   0 /target/debug/build/x11-5b80cb4da447746c/build-script-build\n18.141  rustc            308757 308583   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"pkg-config\" --check-cfg cfg(docsrs,test) ...\n18.171  rustc            308765 308528   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name x11 --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"all\", \"dox\", \"dpms\", \"glx\", \"xcursor\", \"xf86vmode\", \"xfixes\", \"xft\", \"xinerama\", \"xinput\", \"xlib\", \"xlib_xc -C metadata=22d130f92e665544 ...\n18.238  cc               308788 308757   0 /tmp/native-trace-308481-1783993843030/shims/cc -m64 /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/rustcqe1756/symbols.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.03sx8cpjf2ocjut57veg2bgs8.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.1w7a8mqkqkoq1y9i32ajvcgsf.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.3frbdn84inccfq2ljrasvkxov.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.46k5jenuyqpw08831gww4nysh.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.4kfnscuxrkmnv941he0qvdupv.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.6smau0y4fw6mq9vacn9k5ma0s.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.7864bt208ifxqgyti1gl1xfuk.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.7u2tpg0qgpx4wk3jppfk4tdzi.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.8rtl4hgzinygzde3cy5vs66py.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.c92o4p3xek8y97co3g7geiosf.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.d4hg4o1y9k5vtz47028d2m6pu.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.dqlqrbawxyeuuuhr15h7r37of.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.dxbd559uoc94qky1fji60pnnh.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.e8091drgsa8g8qwjo7nf0v7z8.0luh8mn.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libpkg_config-15486b590baf4edc.rlib ...\n18.240  cc               308789 308788   0 /usr/bin/cc -m64 /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/rustcqe1756/symbols.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.03sx8cpjf2ocjut57veg2bgs8.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.1w7a8mqkqkoq1y9i32ajvcgsf.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.3frbdn84inccfq2ljrasvkxov.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.46k5jenuyqpw08831gww4nysh.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.4kfnscuxrkmnv941he0qvdupv.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.6smau0y4fw6mq9vacn9k5ma0s.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.7864bt208ifxqgyti1gl1xfuk.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.7u2tpg0qgpx4wk3jppfk4tdzi.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.8rtl4hgzinygzde3cy5vs66py.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.c92o4p3xek8y97co3g7geiosf.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.d4hg4o1y9k5vtz47028d2m6pu.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.dqlqrbawxyeuuuhr15h7r37of.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.dxbd559uoc94qky1fji60pnnh.0luh8mn.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.e8091drgsa8g8qwjo7nf0v7z8.0luh8mn.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libpkg_config-15486b590baf4edc.rlib ...\n18.247  collect2         308790 308789   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccCle67m.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.250  ld.lld           308791 308790   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccCle67m.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9 ...\n18.255  rust-lld         308791 308790   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccCle67m.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.255  rustc            308793 308620   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"pkg-config\" --check-cfg cfg(docsrs,test) ...\n18.337  powerpc64le-lin  308813 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n18.347  powerpc64le-lin  308814 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n18.349  cc1plus          308815 308813   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n18.350  cc1plus          308816 308814   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n18.392  build-script-bu  308831 308583   0 /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build-script-build\n18.394  pkg-config       308834 308831   0 /tmp/native-trace-308481-1783993843030/shims/pkg-config --libs --cflags dbus-1 dbus-1 >= 1.6\n18.395  pkg-config       308835 308834   0 /usr/bin/pkg-config --libs --cflags dbus-1 dbus-1 >= 1.6\n18.407  cc               308836 308793   0 /tmp/native-trace-308372-1783993842718/shims/cc -m64 /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/rustc6lq0oZ/symbols.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.03sx8cpjf2ocjut57veg2bgs8.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.1w7a8mqkqkoq1y9i32ajvcgsf.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.3frbdn84inccfq2ljrasvkxov.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.46k5jenuyqpw08831gww4nysh.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.4kfnscuxrkmnv941he0qvdupv.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.6smau0y4fw6mq9vacn9k5ma0s.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.7864bt208ifxqgyti1gl1xfuk.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.7u2tpg0qgpx4wk3jppfk4tdzi.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.8rtl4hgzinygzde3cy5vs66py.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.c92o4p3xek8y97co3g7geiosf.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.d4hg4o1y9k5vtz47028d2m6pu.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.dqlqrbawxyeuuuhr15h7r37of.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.dxbd559uoc94qky1fji60pnnh.04b5br9.rcgu.o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9.e8091drgsa8g8qwjo7nf0v7z8.04b5br9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libpkg_config-15486b590baf4edc.rlib ...\n18.409  cc               308837 308836   0 \n18.417  collect2         308838 308837   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc5CCs4n.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.420  ld.lld           308839 308838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc5CCs4n.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build_script_build-1a3e2adc08b5dad9 ...\n18.421  rust-lld         308839 308838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc5CCs4n.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.599  build-script-bu  308857 308620   0 /target/debug/build/libdbus-sys-1a3e2adc08b5dad9/build-script-build\n18.601  pkg-config       308858 308857   0 /tmp/native-trace-308372-1783993842718/shims/pkg-config --libs --cflags dbus-1 dbus-1 >= 1.6\n18.603  pkg-config       308859 308858   0 /usr/bin/pkg-config --libs --cflags dbus-1 dbus-1 >= 1.6\n18.666  powerpc64le-lin  308860 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n18.669  cc1plus          308861 308860   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n18.736  runc             308862 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process2230170049 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n18.750  exe              308870 308862   0 /proc/self/exe init\n18.768  curl             308872 308862   0 /usr/bin/curl -f http://localhost:9091/healthz\n19.027  as               308879 307220   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/a357d10ea739bc2c-adaptive_table_factory.o /tmp/cc8YI2WH.s\n19.106  as               308880 301477   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/9b96b3b3b98b387b-write_buffer_manager.o /tmp/ccrLGkMr.s\n19.167  as               308881 306196   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-filter_policy.o /tmp/ccgmoz0g.s\n19.197  runc             308882 306331   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/785f2834218e0c5aa85c3f869434afca5f72bbb169e4e1db517f0943746 --log-format json --systemd-cgroup kill --all 785f2834218e0c5aa85c3f869434afca5f72bbb169e4e1db517f094374635af3 9\n19.228  runc             308888 306331   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/785f2834218e0c5aa85c3f869434afca5f72bbb169e4e1db517f0943746 --log-format json --systemd-cgroup delete 785f2834218e0c5aa85c3f869434afca5f72bbb169e4e1db517f094374635af3\n19.275  powerpc64le-lin  308894 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n19.284  cc1plus          308895 308894   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n19.472  containerd-shim  308901 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 785f2834218e0c5aa85c3f869434afca5f72bbb169e4e1db517f094374635af3 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/785f2834218e0c5aa85c3f869434afca5f72bbb169e4e1db517f0943746 delete\n19.478  runc             308909 308901   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/785f2834218e0c5aa85c3f869434afca5f72bbb169e4e1db517f094374635af --log-format json delete --force 785f2834218e0c5aa85c3f869434afca5f72bbb169e4e1db517f094374635af3\n19.553  systemd-sysctl   308939 308938   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc657b59 --prefix=/net/ipv4/neigh/vethc657b59 --prefix=/net/ipv6/conf/vethc657b59 --prefix=/net/ipv6/neigh/vethc657b59\n19.595  as               308941 307483   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/053adb4869b9269c-full_filter_block.o /tmp/cc5hrJN4.s\n"
    },
    {
      "argv": [
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 306978,
      "build_script_target_dir": "io-uring-ea6b6ff132ca8689",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build",
      "pid": 306978,
      "ppid": 306862,
      "root_cargo_pid": 306862,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/libc-1f865bb516326eef/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 307012,
      "build_script_target_dir": "libc-1f865bb516326eef",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/libc-1f865bb516326eef/build-script-build",
      "pid": 307012,
      "ppid": 306862,
      "root_cargo_pid": 306862,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 307012,
      "build_script_target_dir": "libc-1f865bb516326eef",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 307013,
      "ppid": 307012,
      "root_cargo_pid": 306862,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "io-uring",
      "cwd": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "event_id": "bsrun:7203d1786fb49915:7834fb0e631a74d9:c734c2099efb859a",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
      "out_dir": "/target/debug/build/io-uring-ea6b6ff132ca8689/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
      "success": true,
      "target": null,
      "version": "0.7.9",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-s4_usfve/src/io-uring-0.7.9",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "libc",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
      "event_id": "bsrun:3a1186cd8cfe6ec2:851b2d1179e7fd28:6fc17f8c88bab7fd",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/libc-1f865bb516326eef/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
      "out_dir": "/target/debug/build/libc-1f865bb516326eef/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
      "success": true,
      "target": null,
      "version": "0.2.156",
      "_owner": {
        "crate": "libc",
        "version": "0.2.156",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.156",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
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
      "build_script_root_pid": 307012,
      "build_script_target_dir": "libc-1f865bb516326eef",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 307013,
      "ppid": 307012,
      "root_cargo_pid": 306862,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 1425,
    "crate": "io-uring",
    "version": "0.7.9",
    "crate_id": "137876",
    "version_id": "1652932",
    "downloads": 12635845,
    "cumulative_downloads": 96279235407,
    "cumulative_share_of_global": 0.3599658345653991,
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
