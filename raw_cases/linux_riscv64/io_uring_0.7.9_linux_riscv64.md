# `io-uring` `0.7.9`

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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK",
    "/target/debug/build/io-uring-ea6b6ff132ca8689",
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
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-305788-1783993821777181536.map",
  "pid": 305788,
  "ppid": 305749,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-305788-1783993821777181536.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
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
  "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "workspace_root": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9"
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
      "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
      "name": "io-uring",
      "version": "0.7.9",
      "manifest_path": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9"
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
    "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "exit_code": 0,
  "kind": "exec",
  "pid": 305788,
  "ppid": 305749,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "event_id": "used:cc:0655d99c389490ff:924d6fa54d017b4e:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
  "pid": 305788,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "event_id": "used:cc:0655d99c389490ff:a0b4fd2dcd0c0445:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
  "pid": 305788,
  "sha256": "c54b5bfc848fc9223e8c32ffdd709e7443c5d69517a8bed20da5cd133df8faca",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "event_id": "used:cc:0655d99c389490ff:80358122d0869d0f:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
  "pid": 305788,
  "sha256": "1e71a9a93e9d04e1656b8581fc0f0e3cbe7bc58b0bc172ab1363460f60c02e4e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "event_id": "used:cc:0655d99c389490ff:269ebc5968a338df:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
  "pid": 305788,
  "sha256": "e074e807ac5a328a27b9a3ccd5947433dae6ee3b5cd29a590ecd2718a303159c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "event_id": "used:cc:0655d99c389490ff:cd78d511c2f04caa:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
  "pid": 305788,
  "sha256": "f30ac6f2d0693c8870aaac97f1b7bd585843ba8e92b69c0e002f8d2097db4168",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "event_id": "used:cc:0655d99c389490ff:6cf05fa21ec5d0d8:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
  "pid": 305788,
  "sha256": "259877a6f889552e34f1e122e5ac8f113947bd1e4b997145953f8dd7b065c060",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "event_id": "used:cc:0655d99c389490ff:d893aad69d4b7983:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
  "pid": 305788,
  "sha256": "3af835e5093441169fb0d882955aabc94139e50dc80cc14318f557216eadcc79",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "event_id": "used:cc:0655d99c389490ff:d6d03ba2315539b8:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
  "pid": 305788,
  "sha256": "19fb2eeea9364d7061347a67eb332563a7bbc8fc2340cd95e11b69ef53605881",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "cargo_pkg_name": "io-uring",
  "cargo_pkg_version": "0.7.9",
  "context_path": "/tmp/native-trace-305459-1783993817058/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-305459-1783993817058/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 305788,
  "ppid": 305749,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK",
    "/target/debug/build/io-uring-ea6b6ff132ca8689",
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
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-305788-1783993821777181536.map",
  "pid": 305788,
  "ppid": 305749,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-305788-1783993821777181536.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
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
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/raw-dylibs",
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
  "pid": 305862,
  "ppid": 305746,
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
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/raw-dylibs",
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
  "event_id": "used:cc:bf4e8db12c663bbd:b485f6e11c53877f:c338943aef9d968a",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
  "path": "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
  "pid": 305862,
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
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/raw-dylibs",
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
  "pid": 305862,
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
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/raw-dylibs",
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
  "pid": 305862,
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
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/raw-dylibs",
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
  "pid": 305862,
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
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/raw-dylibs",
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
  "pid": 305862,
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
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/raw-dylibs",
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
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/raw-dylibs",
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
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/raw-dylibs",
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
  "context_path": "/tmp/native-trace-305459-1783993817058/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-305459-1783993817058/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 305862,
  "ppid": 305746,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
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
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/raw-dylibs",
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
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ",
    "/target/debug/build/libc-1f865bb516326eef",
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
      "directory": "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ",
      "kind": "object",
      "path": "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
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
  "map_path": "/tmp/native-trace-link-cc-305862-1783993821930795568.map",
  "pid": 305862,
  "ppid": 305746,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-305862-1783993821930795568.map"
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
  "parse_error_count": 2,
  "parsed_event_count": 446,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 448,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n8.428   collect2         306955 306954   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccCtzfZB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n8.432   ld.lld           306956 306955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccCtzfZB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689 ...\n8.438   rust-lld         306956 306955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccCtzfZB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n8.514   build-script-bu  306975 306787   0 /target/debug/build/x11-5b80cb4da447746c/build-script-build\n8.549   build-script-bu  306978 306862   0 /target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build\n8.611   rustc            306984 306787   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name x11 --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"all\", \"dox\", \"dpms\", \"glx\", \"xcursor\", \"xf86vmode\", \"xfixes\", \"xft\", \"xinerama\", \"xinput\", \"xlib\", \"xlib_xc -C metadata=5080a35008614888 ...\n8.622   aarch64-linux-g  306986 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n8.622   cc               306987 306881   0 /tmp/native-trace-306534-1783993825592/shims/cc -m64 /target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n8.623   cc               306988 306987   0 /usr/bin/cc -m64 /target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n8.627   collect2         306993 306988   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoCyuab.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n8.631   cc1plus          306992 306986   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n8.762   ld.lld           306994 306993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoCyuab.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef ...\n8.764   rust-lld         306994 306993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoCyuab.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n8.912   build-script-bu  307012 306862   0 /target/debug/build/libc-1f865bb516326eef/build-script-build\n8.915   rustc            307013 307012   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n8.954   rustc            307018 306862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\" -C metadata=ef50dfd2da3fa8f6 ...\n9.260   powerpc64le-lin  307022 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n9.273   cc1plus          307023 307022   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n9.277   as               307024 304991   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/94ad6eef41e52848-options.o /tmp/ccjnXIu5.s\n9.389   as               307025 305784   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/8d9638b5dd27dacb-thread_status_updater.o /tmp/ccQOJJvb.s\n9.444   rustc            307029 306862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name io_uring --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"bindgen\", \"direct-syscall\", \"io_safety\", \"overwrite\", \"sc\")) -C metadata=24c87ebdb0a15170 ...\n9.875   as               307034 283962   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/3ac6d140080a8125-version_set.o /tmp/ccd22lF6.s\n9.930   riscv64-linux-g  307035 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n9.935   cc1plus          307036 307035   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n10.290  powerpc64le-lin  307065 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n10.299  cc1plus          307066 307065   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n10.706  as               307148 305901   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/8d9638b5dd27dacb-thread_status_util_debug. /tmp/cchgmAWZ.s\n10.730  runc             307149 301343   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee38 --log-format json --systemd-cgroup kill --all 5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee3869795 9\n10.740  as               307155 305768   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-block_prefetcher.o /tmp/cchUWb2U.s\n10.782  runc             307156 301343   0 \n10.907  powerpc64le-lin  307162 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n10.914  cc1plus          307163 307162   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n10.961  containerd-shim  307164 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee3869795 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee38 delete\n10.967  runc             307171 307164   0 \n11.022  sh               307179 307176   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth2983a03\n11.027  ethtool          307180 307179   0 /usr/sbin/ethtool -i veth2983a03\n11.027  sed              307181 307179   0 /usr/bin/sed -n s/^driver: //p\n11.039  systemd-sysctl   307184 307176   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2983a03 --prefix=/net/ipv4/neigh/veth2983a03 --prefix=/net/ipv6/conf/veth2983a03 --prefix=/net/ipv6/neigh/veth2983a03\n11.127  rustup           307186 300818   0 \n11.341  as               307195 307065   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/1938569c7fa5575d-mmap.o /tmp/ccEKTJ82.s\n11.382  as               307196 301436   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/94ad6eef41e52848-cf_options.o /tmp/cci4aqh1.s\n11.433  cargo            307197 306769   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n11.456  rustc            307198 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n11.494  rustc            307204 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.139/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n11.499  rustc            307206 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pkg_config --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.26/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=3b393852d2f0042a ...\n11.535  powerpc64le-lin  307213 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n11.541  cc1plus          307214 307213   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n11.588  as               307215 307213   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/1938569c7fa5575d-stack_trace.o /tmp/cc8iHRTd.s\n11.675  powerpc64le-lin  307220 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n11.680  cc               307221 307204   0 /tmp/native-trace-306769-1783993828472/shims/cc -m64 /target/debug/build/libc-d5e24a35c6204c3a/rustcE96TYb/symbols.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.0.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.1.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.f2zdzhd5zba24j4jlc52eo9qw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n11.683  cc               307223 307221   0 /usr/bin/cc -m64 /target/debug/build/libc-d5e24a35c6204c3a/rustcE96TYb/symbols.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.0.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.1.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.f2zdzhd5zba24j4jlc52eo9qw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n11.687  cc1plus          307222 307220   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n11.687  collect2         307224 307223   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cceL2jFQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.693  ld.lld           307225 307224   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cceL2jFQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a ...\n11.697  rust-lld         307225 307224   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cceL2jFQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.804  build-script-bu  307245 307197   0 /target/debug/build/libc-d5e24a35c6204c3a/build-script-build\n11.806  rustc            307246 307245   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n11.829  rustc            307250 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.139/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n11.836  as               307252 300174   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/8d9638b5dd27dacb-persistent_stats_history.o /tmp/cccCVpdD.s\n12.024  rustc            307265 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"all\", \"dox\", \"dpms\", \"glx\", \"xcursor\", \"xf86vmode\", \"xfixes\", \"xft\", \"xinerama\", \"xinput\", \"xlib\", \"xlib_xc -C metadata=255bbe92912e964c ...\n12.179  cc               307291 307265   0 /tmp/native-trace-306769-1783993828472/shims/cc -m64 /target/debug/build/x11-5b80cb4da447746c/rustc0FDdz7/symbols.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.0qpi4mfmdotxvbce65x1xolh5.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.1y5yvu9jfka2c9w6hdajk52mn.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2pgg0dydoon132lopfe3oeztn.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2xh8j4d4a8yjbzwckhvntue0x.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.39j5lffqj7iy9ky93lf4m1dvl.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.3hkihxlli2q3axu4j61quupxj.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.44rz59wt54t9whocyj6tl3sy6.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.4yf6piehmld0y3l6zfsp08p38.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5afi2faxvl1q1vcdkgjl4nd14.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5vhsfxiiyspcnnavjjajlnp0z.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6apyjtfohf32ep2noq6qjeum7.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6iul0kjx749ugjo89pfuv6u0w.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7it1b9op5prid5fjylbt91g33.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7tq31ucs1ym2b1in8e7evpg2l.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8g3fir08766ptuc0avn1jc9o0.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8sze6dttyazzx1z68t3af3lec.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.9axw8cp9299kam4l1cekxkbkl.0yidy89.rcgu.o ...\n12.181  cc               307292 307291   0 /usr/bin/cc -m64 /target/debug/build/x11-5b80cb4da447746c/rustc0FDdz7/symbols.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.0qpi4mfmdotxvbce65x1xolh5.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.1y5yvu9jfka2c9w6hdajk52mn.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2pgg0dydoon132lopfe3oeztn.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2xh8j4d4a8yjbzwckhvntue0x.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.39j5lffqj7iy9ky93lf4m1dvl.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.3hkihxlli2q3axu4j61quupxj.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.44rz59wt54t9whocyj6tl3sy6.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.4yf6piehmld0y3l6zfsp08p38.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5afi2faxvl1q1vcdkgjl4nd14.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5vhsfxiiyspcnnavjjajlnp0z.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6apyjtfohf32ep2noq6qjeum7.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6iul0kjx749ugjo89pfuv6u0w.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7it1b9op5prid5fjylbt91g33.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7tq31ucs1ym2b1in8e7evpg2l.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8g3fir08766ptuc0avn1jc9o0.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8sze6dttyazzx1z68t3af3lec.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.9axw8cp9299kam4l1cekxkbkl.0yidy89.rcgu.o ...\n12.186  collect2         307293 307292   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwSdjuu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n12.190  ld.lld           307294 307293   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwSdjuu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c ...\n12.195  rust-lld         307294 307293   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwSdjuu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n12.238  aarch64-linux-g  307311 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n12.248  cc1plus          307312 307311   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n12.303  runc             307314 301759   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ceb9e0963e26c3db3021b259eb93edf9c88ec5ccc3f2c9e953edecf3991 --log-format json --systemd-cgroup kill --all ceb9e0963e26c3db3021b259eb93edf9c88ec5ccc3f2c9e953edecf3991c551b 9\n12.313  build-script-bu  307321 307197   0 \n12.321  rustc            307325 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name x11 --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"all\", \"dox\", \"dpms\", \"glx\", \"xcursor\", \"xf86vmode\", \"xfixes\", \"xft\", \"xinerama\", \"xinput\", \"xlib\", \"xlib_xc -C metadata=795ab2a413e3bdba ...\n12.331  runc             307327 301759   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ceb9e0963e26c3db3021b259eb93edf9c88ec5ccc3f2c9e953edecf3991 --log-format json --systemd-cgroup delete ceb9e0963e26c3db3021b259eb93edf9c88ec5ccc3f2c9e953edecf3991c551b\n12.398  runc             307336 303412   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3e3db6508747630a4e7363eaff775dfa0ff0ed740194f8918495e429e5c --log-format json --systemd-cgroup kill --all 3e3db6508747630a4e7363eaff775dfa0ff0ed740194f8918495e429e5c65603 9\n12.422  runc             307342 303412   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3e3db6508747630a4e7363eaff775dfa0ff0ed740194f8918495e429e5c --log-format json --systemd-cgroup delete 3e3db6508747630a4e7363eaff775dfa0ff0ed740194f8918495e429e5c65603\n12.517  as               307349 307162   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/1938569c7fa5575d-port_posix.o /tmp/ccn9sWkm.s\n12.577  containerd-shim  307350 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id ceb9e0963e26c3db3021b259eb93edf9c88ec5ccc3f2c9e953edecf3991c551b -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ceb9e0963e26c3db3021b259eb93edf9c88ec5ccc3f2c9e953edecf3991 delete\n12.581  runc             307357 307350   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ceb9e0963e26c3db3021b259eb93edf9c88ec5ccc3f2c9e953edecf3991c551 --log-format json delete --force ceb9e0963e26c3db3021b259eb93edf9c88ec5ccc3f2c9e953edecf3991c551b\n12.627  sh               307364 307185   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth3bf553a\n12.631  ethtool          307365 307364   0 /usr/sbin/ethtool -i veth3bf553a\n12.633  sed              307367 307364   0 /usr/bin/sed -n s/^driver: //p\n12.646  systemd-sysctl   307370 307185   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth3bf553a --prefix=/net/ipv4/neigh/veth3bf553a --prefix=/net/ipv6/conf/veth3bf553a --prefix=/net/ipv6/neigh/veth3bf553a\n12.701  powerpc64le-lin  307372 229287   0 \n12.703  cc1plus          307374 307372   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n12.706  rustup           307375 301600   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n12.717  powerpc64le-lin  307373 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n12.729  cc1plus          307384 307373   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n12.735  containerd-shim  307385 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 3e3db6508747630a4e7363eaff775dfa0ff0ed740194f8918495e429e5c65603 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3e3db6508747630a4e7363eaff775dfa0ff0ed740194f8918495e429e5c delete\n12.740  runc             307392 307385   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3e3db6508747630a4e7363eaff775dfa0ff0ed740194f8918495e429e5c6560 --log-format json delete --force 3e3db6508747630a4e7363eaff775dfa0ff0ed740194f8918495e429e5c65603\n12.781  riscv64-linux-g  307397 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n12.786  systemd-sysctl   307398 307185   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth1720391 --prefix=/net/ipv4/neigh/veth1720391 --prefix=/net/ipv6/conf/veth1720391 --prefix=/net/ipv6/neigh/veth1720391\n12.796  cc1plus          307399 307397   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n13.014  runc             307401 301513   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a755148bb77721f3e75a0b8eeaf6fe5daf57096e6f7afc9c601209734d2 --log-format json --systemd-cgroup kill --all a755148bb77721f3e75a0b8eeaf6fe5daf57096e6f7afc9c601209734d227544 9\n13.016  as               307400 306783   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/053adb4869b9269c-block_builder.o /tmp/ccGLrixg.s\n13.061  runc             307407 301513   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a755148bb77721f3e75a0b8eeaf6fe5daf57096e6f7afc9c601209734d2 --log-format json --systemd-cgroup delete a755148bb77721f3e75a0b8eeaf6fe5daf57096e6f7afc9c601209734d227544\n13.141  as               307413 298454   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/9b96b3b3b98b387b-write_buffer_manager.o /tmp/ccchY47w.s\n13.275  containerd-shim  307414 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a755148bb77721f3e75a0b8eeaf6fe5daf57096e6f7afc9c601209734d227544 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a755148bb77721f3e75a0b8eeaf6fe5daf57096e6f7afc9c601209734d2 delete\n13.282  runc             307421 307414   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a755148bb77721f3e75a0b8eeaf6fe5daf57096e6f7afc9c601209734d22754 --log-format json delete --force a755148bb77721f3e75a0b8eeaf6fe5daf57096e6f7afc9c601209734d227544\n13.346  systemd-sysctl   307426 307185   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth13e5aa5 --prefix=/net/ipv4/neigh/veth13e5aa5 --prefix=/net/ipv6/conf/veth13e5aa5 --prefix=/net/ipv6/neigh/veth13e5aa5\n13.428  rustup           307428 301076   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n13.431  riscv64-linux-g  307427 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n13.437  riscv64-linux-g  307437 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n13.441  riscv64-linux-g  307438 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n13.443  cc1plus          307439 307427   0 \n13.446  cc1plus          307440 307437   0 \n13.446  cc1plus          307441 307438   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n13.633  as               307451 306803   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/94ad6eef41e52848-offpeak_time_info.o /tmp/cc5CtDjd.s\n13.660  16               307468 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n13.682  frpc             307468 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n13.832  as               307476 304468   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/94ad6eef41e52848-db_options.o /tmp/ccK4O0xv.s\n13.924  as               307477 305618   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/a357d10ea739bc2c-adaptive_table_factory.o /tmp/ccL43ckf.s\n14.189  as               307478 307397   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/053adb4869b9269c-data_block_hash_index.o /tmp/cc5GAu3s.s\n14.203  as               307479 305026   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/94ad6eef41e52848-options_helper.o /tmp/ccwo695W.s\n14.257  powerpc64le-lin  307480 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n14.264  cc1plus          307481 307480   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n14.449  riscv64-linux-g  307482 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n14.451  riscv64-linux-g  307483 229324   0 \n14.455  cc1plus          307484 307482   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n14.461  cc1plus          307485 307483   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n14.755  riscv64-linux-g  307486 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n14.766  cc1plus          307487 307486   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n14.941  as               307488 306512   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/94ad6eef41e52848-configurable.o /tmp/ccZRosjc.s\n15.286  as               307489 306556   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/94ad6eef41e52848-customizable.o /tmp/ccibq38v.s\n15.631  as               307490 307035   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/053adb4869b9269c-block_prefix_index.o /tmp/cc6jZMBq.s\n15.772  powerpc64le-lin  307491 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n15.776  cc1plus          307493 307491   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n15.794  powerpc64le-lin  307492 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n15.804  cc1plus          307494 307492   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n15.922  as               307495 306195   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-filter_block_reader_common.o /tmp/cc3OYL6b.s\n15.948  as               307496 306681   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-index_reader_common.o /tmp/cc2gQpS0.s\n16.072  as               307497 305631   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/8d9638b5dd27dacb-statistics.o /tmp/ccCYEUpz.s\n16.085  as               307498 305029   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/94ad6eef41e52848-options_parser.o /tmp/ccH43egk.s\n16.166  as               307499 305554   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-block_cache.o /tmp/ccJsEO5J.s\n16.283  riscv64-linux-g  307500 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n16.293  cc1plus          307502 307500   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n16.295  riscv64-linux-g  307501 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n16.303  cc1plus          307503 307501   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n16.426  powerpc64le-lin  307504 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n16.431  cc1plus          307505 307504   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n16.620  riscv64-linux-g  307506 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n16.626  cc1plus          307507 307506   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n16.758  aarch64-linux-g  307508 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n16.763  cc1plus          307510 307508   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n16.763  aarch64-linux-g  307509 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n16.769  cc1plus          307511 307509   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n16.782  aarch64-linux-g  307512 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n16.790  cc1plus          307513 307512   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n16.923  as               307514 305620   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/053adb4869b9269c-binary_search_index_reader. /tmp/cc2T5Ir5.s\n17.235  riscv64-linux-g  307515 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n17.244  cc1plus          307516 307515   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n17.390  as               307517 307427   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/053adb4869b9269c-data_block_footer.o /tmp/ccKR64Mb.s\n17.560  riscv64-linux-g  307518 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n17.567  cc1plus          307519 307518   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n18.090  as               307520 306198   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-flush_block_policy.o /tmp/ccFhNTAt.s\n18.131  as               307521 305787   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/8d9638b5dd27dacb-thread_status_updater_deb /tmp/cc3jgnNm.s\n18.165  as               307522 306136   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/94ad6eef41e52848-cf_options.o /tmp/cc6z5BcL.s\n18.388  as               307523 306922   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/053adb4869b9269c-block_prefetcher.o /tmp/cccWWTBU.s\n18.434  as               307524 306318   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-full_filter_block.o /tmp/cczF3RZv.s\n18.489  runc             307525 300930   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/55015dff9db4fc35415c3e1e329a4cdd0c9f0ade6a99f54d541e36a0531 --log-format json --systemd-cgroup kill --all 55015dff9db4fc35415c3e1e329a4cdd0c9f0ade6a99f54d541e36a0531d827c 9\n18.511  runc             307531 300930   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/55015dff9db4fc35415c3e1e329a4cdd0c9f0ade6a99f54d541e36a0531 --log-format json --systemd-cgroup delete 55015dff9db4fc35415c3e1e329a4cdd0c9f0ade6a99f54d541e36a0531d827c\n18.548  as               307537 306781   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-parsed_full_filter_block.o /tmp/ccVEJdQv.s\n18.583  powerpc64le-lin  307538 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n18.593  cc1plus          307539 307538   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n18.734  containerd-shim  307541 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 55015dff9db4fc35415c3e1e329a4cdd0c9f0ade6a99f54d541e36a0531d827c -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/55015dff9db4fc35415c3e1e329a4cdd0c9f0ade6a99f54d541e36a0531 delete\n18.739  runc             307548 307541   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/55015dff9db4fc35415c3e1e329a4cdd0c9f0ade6a99f54d541e36a0531d827 --log-format json delete --force 55015dff9db4fc35415c3e1e329a4cdd0c9f0ade6a99f54d541e36a0531d827c\n18.785  systemd-sysctl   307554 307553   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetheeaee50 --prefix=/net/ipv4/neigh/vetheeaee50 --prefix=/net/ipv6/conf/vetheeaee50 --prefix=/net/ipv6/neigh/vetheeaee50\n18.909  aarch64-linux-g  307556 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n18.916  cc1plus          307558 307556   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n18.917  aarch64-linux-g  307557 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n18.924  cc1plus          307559 307557   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n19.234  aarch64-linux-g  307560 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n19.245  cc1plus          307561 307560   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n19.315  runc             307562 301257   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9298839e331017280ebb70d2917cb62fa9ffdb09a76a2ae3f0b7fd00897 --log-format json --systemd-cgroup kill --all 9298839e331017280ebb70d2917cb62fa9ffdb09a76a2ae3f0b7fd0089717fc1 9\n19.343  runc             307568 301257   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9298839e331017280ebb70d2917cb62fa9ffdb09a76a2ae3f0b7fd00897 --log-format json --systemd-cgroup delete 9298839e331017280ebb70d2917cb62fa9ffdb09a76a2ae3f0b7fd0089717fc1\n"
}
```

#### Record 25

```json
{
  "argv": [
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 305861,
  "build_script_target_dir": "io-uring-ea6b6ff132ca8689",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build",
  "pid": 305861,
  "ppid": 305736,
  "root_cargo_pid": 305736,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
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
  "build_script_root_pid": 305887,
  "build_script_target_dir": "libc-1f865bb516326eef",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/libc-1f865bb516326eef/build-script-build",
  "pid": 305887,
  "ppid": 305736,
  "root_cargo_pid": 305736,
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
  "build_script_root_pid": 305887,
  "build_script_target_dir": "libc-1f865bb516326eef",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 305889,
  "ppid": 305887,
  "root_cargo_pid": 305736,
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
  "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "event_id": "bsrun:e40eb6ef14bfe16a:7834fb0e631a74d9:c734c2099efb859a",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
  "out_dir": "/target/debug/build/io-uring-ea6b6ff132ca8689/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
  "success": true,
  "target": null,
  "version": "0.7.9",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
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
  "build_script_root_pid": 305887,
  "build_script_target_dir": "libc-1f865bb516326eef",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 305889,
  "ppid": 305887,
  "root_cargo_pid": 305736,
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
  "time": "2026-07-14T01:50:46.615178+00:00",
  "crate": "io-uring",
  "version": "0.7.9",
  "architecture": "riscv64",
  "duration_seconds": 34.64522559288889,
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
        "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
        "manifest_path": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9/Cargo.toml"
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
      "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
      "workspace_root": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9"
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
          "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
          "name": "io-uring",
          "version": "0.7.9",
          "manifest_path": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9"
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
        "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
      "exit_code": 0,
      "kind": "exec",
      "pid": 305788,
      "ppid": 305749,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
      "event_id": "used:cc:0655d99c389490ff:924d6fa54d017b4e:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
      "pid": 305788,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
      "event_id": "used:cc:0655d99c389490ff:a0b4fd2dcd0c0445:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
      "pid": 305788,
      "sha256": "c54b5bfc848fc9223e8c32ffdd709e7443c5d69517a8bed20da5cd133df8faca",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
      "event_id": "used:cc:0655d99c389490ff:80358122d0869d0f:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
      "pid": 305788,
      "sha256": "1e71a9a93e9d04e1656b8581fc0f0e3cbe7bc58b0bc172ab1363460f60c02e4e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
      "event_id": "used:cc:0655d99c389490ff:269ebc5968a338df:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
      "pid": 305788,
      "sha256": "e074e807ac5a328a27b9a3ccd5947433dae6ee3b5cd29a590ecd2718a303159c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
      "event_id": "used:cc:0655d99c389490ff:cd78d511c2f04caa:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
      "pid": 305788,
      "sha256": "f30ac6f2d0693c8870aaac97f1b7bd585843ba8e92b69c0e002f8d2097db4168",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
      "event_id": "used:cc:0655d99c389490ff:6cf05fa21ec5d0d8:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
      "pid": 305788,
      "sha256": "259877a6f889552e34f1e122e5ac8f113947bd1e4b997145953f8dd7b065c060",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
      "event_id": "used:cc:0655d99c389490ff:d893aad69d4b7983:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
      "pid": 305788,
      "sha256": "3af835e5093441169fb0d882955aabc94139e50dc80cc14318f557216eadcc79",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
      "event_id": "used:cc:0655d99c389490ff:d6d03ba2315539b8:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
      "pid": 305788,
      "sha256": "19fb2eeea9364d7061347a67eb332563a7bbc8fc2340cd95e11b69ef53605881",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
      "cargo_pkg_name": "io-uring",
      "cargo_pkg_version": "0.7.9",
      "context_path": "/tmp/native-trace-305459-1783993817058/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-305459-1783993817058/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 305788,
      "ppid": 305749,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK",
        "/target/debug/build/io-uring-ea6b6ff132ca8689",
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
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcARw6YK/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0iwdalm.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0iwdalm.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0iwdalm.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0iwdalm.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0iwdalm.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0iwdalm.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0iwdalm.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-305788-1783993821777181536.map",
      "pid": 305788,
      "ppid": 305749,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-305788-1783993821777181536.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/raw-dylibs",
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
      "pid": 305862,
      "ppid": 305746,
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
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/raw-dylibs",
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
      "event_id": "used:cc:bf4e8db12c663bbd:b485f6e11c53877f:c338943aef9d968a",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
      "path": "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
      "pid": 305862,
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
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/raw-dylibs",
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
      "pid": 305862,
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
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/raw-dylibs",
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
      "pid": 305862,
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
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/raw-dylibs",
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
      "pid": 305862,
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
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/raw-dylibs",
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
      "pid": 305862,
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
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/raw-dylibs",
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
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/raw-dylibs",
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
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/raw-dylibs",
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
      "context_path": "/tmp/native-trace-305459-1783993817058/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-305459-1783993817058/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 305862,
      "ppid": 305746,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
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
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/raw-dylibs",
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
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ",
        "/target/debug/build/libc-1f865bb516326eef",
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
          "directory": "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ",
          "kind": "object",
          "path": "/target/debug/build/libc-1f865bb516326eef/rustc6EFkqZ/symbols.o",
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
      "map_path": "/tmp/native-trace-link-cc-305862-1783993821930795568.map",
      "pid": 305862,
      "ppid": 305746,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-305862-1783993821930795568.map"
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
      "parse_error_count": 2,
      "parsed_event_count": 446,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 448,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n8.428   collect2         306955 306954   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccCtzfZB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n8.432   ld.lld           306956 306955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccCtzfZB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689 ...\n8.438   rust-lld         306956 306955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccCtzfZB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n8.514   build-script-bu  306975 306787   0 /target/debug/build/x11-5b80cb4da447746c/build-script-build\n8.549   build-script-bu  306978 306862   0 /target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build\n8.611   rustc            306984 306787   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name x11 --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"all\", \"dox\", \"dpms\", \"glx\", \"xcursor\", \"xf86vmode\", \"xfixes\", \"xft\", \"xinerama\", \"xinput\", \"xlib\", \"xlib_xc -C metadata=5080a35008614888 ...\n8.622   aarch64-linux-g  306986 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n8.622   cc               306987 306881   0 /tmp/native-trace-306534-1783993825592/shims/cc -m64 /target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n8.623   cc               306988 306987   0 /usr/bin/cc -m64 /target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n8.627   collect2         306993 306988   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoCyuab.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n8.631   cc1plus          306992 306986   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n8.762   ld.lld           306994 306993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoCyuab.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef ...\n8.764   rust-lld         306994 306993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoCyuab.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n8.912   build-script-bu  307012 306862   0 /target/debug/build/libc-1f865bb516326eef/build-script-build\n8.915   rustc            307013 307012   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n8.954   rustc            307018 306862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\" -C metadata=ef50dfd2da3fa8f6 ...\n9.260   powerpc64le-lin  307022 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n9.273   cc1plus          307023 307022   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n9.277   as               307024 304991   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/94ad6eef41e52848-options.o /tmp/ccjnXIu5.s\n9.389   as               307025 305784   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/8d9638b5dd27dacb-thread_status_updater.o /tmp/ccQOJJvb.s\n9.444   rustc            307029 306862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name io_uring --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"bindgen\", \"direct-syscall\", \"io_safety\", \"overwrite\", \"sc\")) -C metadata=24c87ebdb0a15170 ...\n9.875   as               307034 283962   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/3ac6d140080a8125-version_set.o /tmp/ccd22lF6.s\n9.930   riscv64-linux-g  307035 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n9.935   cc1plus          307036 307035   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n10.290  powerpc64le-lin  307065 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n10.299  cc1plus          307066 307065   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n10.706  as               307148 305901   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/8d9638b5dd27dacb-thread_status_util_debug. /tmp/cchgmAWZ.s\n10.730  runc             307149 301343   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee38 --log-format json --systemd-cgroup kill --all 5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee3869795 9\n10.740  as               307155 305768   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-block_prefetcher.o /tmp/cchUWb2U.s\n10.782  runc             307156 301343   0 \n10.907  powerpc64le-lin  307162 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n10.914  cc1plus          307163 307162   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n10.961  containerd-shim  307164 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee3869795 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee38 delete\n10.967  runc             307171 307164   0 \n11.022  sh               307179 307176   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth2983a03\n11.027  ethtool          307180 307179   0 /usr/sbin/ethtool -i veth2983a03\n11.027  sed              307181 307179   0 /usr/bin/sed -n s/^driver: //p\n11.039  systemd-sysctl   307184 307176   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2983a03 --prefix=/net/ipv4/neigh/veth2983a03 --prefix=/net/ipv6/conf/veth2983a03 --prefix=/net/ipv6/neigh/veth2983a03\n11.127  rustup           307186 300818   0 \n11.341  as               307195 307065   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/1938569c7fa5575d-mmap.o /tmp/ccEKTJ82.s\n11.382  as               307196 301436   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/94ad6eef41e52848-cf_options.o /tmp/cci4aqh1.s\n11.433  cargo            307197 306769   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n11.456  rustc            307198 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n11.494  rustc            307204 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.139/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n11.499  rustc            307206 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pkg_config --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.26/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=3b393852d2f0042a ...\n11.535  powerpc64le-lin  307213 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n11.541  cc1plus          307214 307213   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n11.588  as               307215 307213   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/1938569c7fa5575d-stack_trace.o /tmp/cc8iHRTd.s\n11.675  powerpc64le-lin  307220 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n11.680  cc               307221 307204   0 /tmp/native-trace-306769-1783993828472/shims/cc -m64 /target/debug/build/libc-d5e24a35c6204c3a/rustcE96TYb/symbols.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.0.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.1.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.f2zdzhd5zba24j4jlc52eo9qw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n11.683  cc               307223 307221   0 /usr/bin/cc -m64 /target/debug/build/libc-d5e24a35c6204c3a/rustcE96TYb/symbols.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.0.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.1.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.f2zdzhd5zba24j4jlc52eo9qw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n11.687  cc1plus          307222 307220   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n11.687  collect2         307224 307223   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cceL2jFQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.693  ld.lld           307225 307224   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cceL2jFQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a ...\n11.697  rust-lld         307225 307224   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cceL2jFQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.804  build-script-bu  307245 307197   0 /target/debug/build/libc-d5e24a35c6204c3a/build-script-build\n11.806  rustc            307246 307245   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n11.829  rustc            307250 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.139/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n11.836  as               307252 300174   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/8d9638b5dd27dacb-persistent_stats_history.o /tmp/cccCVpdD.s\n12.024  rustc            307265 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"all\", \"dox\", \"dpms\", \"glx\", \"xcursor\", \"xf86vmode\", \"xfixes\", \"xft\", \"xinerama\", \"xinput\", \"xlib\", \"xlib_xc -C metadata=255bbe92912e964c ...\n12.179  cc               307291 307265   0 /tmp/native-trace-306769-1783993828472/shims/cc -m64 /target/debug/build/x11-5b80cb4da447746c/rustc0FDdz7/symbols.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.0qpi4mfmdotxvbce65x1xolh5.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.1y5yvu9jfka2c9w6hdajk52mn.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2pgg0dydoon132lopfe3oeztn.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2xh8j4d4a8yjbzwckhvntue0x.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.39j5lffqj7iy9ky93lf4m1dvl.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.3hkihxlli2q3axu4j61quupxj.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.44rz59wt54t9whocyj6tl3sy6.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.4yf6piehmld0y3l6zfsp08p38.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5afi2faxvl1q1vcdkgjl4nd14.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5vhsfxiiyspcnnavjjajlnp0z.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6apyjtfohf32ep2noq6qjeum7.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6iul0kjx749ugjo89pfuv6u0w.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7it1b9op5prid5fjylbt91g33.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7tq31ucs1ym2b1in8e7evpg2l.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8g3fir08766ptuc0avn1jc9o0.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8sze6dttyazzx1z68t3af3lec.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.9axw8cp9299kam4l1cekxkbkl.0yidy89.rcgu.o ...\n12.181  cc               307292 307291   0 /usr/bin/cc -m64 /target/debug/build/x11-5b80cb4da447746c/rustc0FDdz7/symbols.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.0qpi4mfmdotxvbce65x1xolh5.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.1y5yvu9jfka2c9w6hdajk52mn.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2pgg0dydoon132lopfe3oeztn.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2xh8j4d4a8yjbzwckhvntue0x.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.39j5lffqj7iy9ky93lf4m1dvl.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.3hkihxlli2q3axu4j61quupxj.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.44rz59wt54t9whocyj6tl3sy6.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.4yf6piehmld0y3l6zfsp08p38.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5afi2faxvl1q1vcdkgjl4nd14.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5vhsfxiiyspcnnavjjajlnp0z.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6apyjtfohf32ep2noq6qjeum7.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6iul0kjx749ugjo89pfuv6u0w.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7it1b9op5prid5fjylbt91g33.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7tq31ucs1ym2b1in8e7evpg2l.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8g3fir08766ptuc0avn1jc9o0.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8sze6dttyazzx1z68t3af3lec.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.9axw8cp9299kam4l1cekxkbkl.0yidy89.rcgu.o ...\n12.186  collect2         307293 307292   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwSdjuu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n12.190  ld.lld           307294 307293   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwSdjuu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c ...\n12.195  rust-lld         307294 307293   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwSdjuu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n12.238  aarch64-linux-g  307311 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n12.248  cc1plus          307312 307311   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n12.303  runc             307314 301759   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ceb9e0963e26c3db3021b259eb93edf9c88ec5ccc3f2c9e953edecf3991 --log-format json --systemd-cgroup kill --all ceb9e0963e26c3db3021b259eb93edf9c88ec5ccc3f2c9e953edecf3991c551b 9\n12.313  build-script-bu  307321 307197   0 \n12.321  rustc            307325 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name x11 --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"all\", \"dox\", \"dpms\", \"glx\", \"xcursor\", \"xf86vmode\", \"xfixes\", \"xft\", \"xinerama\", \"xinput\", \"xlib\", \"xlib_xc -C metadata=795ab2a413e3bdba ...\n12.331  runc             307327 301759   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ceb9e0963e26c3db3021b259eb93edf9c88ec5ccc3f2c9e953edecf3991 --log-format json --systemd-cgroup delete ceb9e0963e26c3db3021b259eb93edf9c88ec5ccc3f2c9e953edecf3991c551b\n12.398  runc             307336 303412   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3e3db6508747630a4e7363eaff775dfa0ff0ed740194f8918495e429e5c --log-format json --systemd-cgroup kill --all 3e3db6508747630a4e7363eaff775dfa0ff0ed740194f8918495e429e5c65603 9\n12.422  runc             307342 303412   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3e3db6508747630a4e7363eaff775dfa0ff0ed740194f8918495e429e5c --log-format json --systemd-cgroup delete 3e3db6508747630a4e7363eaff775dfa0ff0ed740194f8918495e429e5c65603\n12.517  as               307349 307162   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/1938569c7fa5575d-port_posix.o /tmp/ccn9sWkm.s\n12.577  containerd-shim  307350 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id ceb9e0963e26c3db3021b259eb93edf9c88ec5ccc3f2c9e953edecf3991c551b -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ceb9e0963e26c3db3021b259eb93edf9c88ec5ccc3f2c9e953edecf3991 delete\n12.581  runc             307357 307350   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ceb9e0963e26c3db3021b259eb93edf9c88ec5ccc3f2c9e953edecf3991c551 --log-format json delete --force ceb9e0963e26c3db3021b259eb93edf9c88ec5ccc3f2c9e953edecf3991c551b\n12.627  sh               307364 307185   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth3bf553a\n12.631  ethtool          307365 307364   0 /usr/sbin/ethtool -i veth3bf553a\n12.633  sed              307367 307364   0 /usr/bin/sed -n s/^driver: //p\n12.646  systemd-sysctl   307370 307185   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth3bf553a --prefix=/net/ipv4/neigh/veth3bf553a --prefix=/net/ipv6/conf/veth3bf553a --prefix=/net/ipv6/neigh/veth3bf553a\n12.701  powerpc64le-lin  307372 229287   0 \n12.703  cc1plus          307374 307372   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n12.706  rustup           307375 301600   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n12.717  powerpc64le-lin  307373 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n12.729  cc1plus          307384 307373   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n12.735  containerd-shim  307385 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 3e3db6508747630a4e7363eaff775dfa0ff0ed740194f8918495e429e5c65603 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3e3db6508747630a4e7363eaff775dfa0ff0ed740194f8918495e429e5c delete\n12.740  runc             307392 307385   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3e3db6508747630a4e7363eaff775dfa0ff0ed740194f8918495e429e5c6560 --log-format json delete --force 3e3db6508747630a4e7363eaff775dfa0ff0ed740194f8918495e429e5c65603\n12.781  riscv64-linux-g  307397 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n12.786  systemd-sysctl   307398 307185   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth1720391 --prefix=/net/ipv4/neigh/veth1720391 --prefix=/net/ipv6/conf/veth1720391 --prefix=/net/ipv6/neigh/veth1720391\n12.796  cc1plus          307399 307397   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n13.014  runc             307401 301513   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a755148bb77721f3e75a0b8eeaf6fe5daf57096e6f7afc9c601209734d2 --log-format json --systemd-cgroup kill --all a755148bb77721f3e75a0b8eeaf6fe5daf57096e6f7afc9c601209734d227544 9\n13.016  as               307400 306783   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/053adb4869b9269c-block_builder.o /tmp/ccGLrixg.s\n13.061  runc             307407 301513   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a755148bb77721f3e75a0b8eeaf6fe5daf57096e6f7afc9c601209734d2 --log-format json --systemd-cgroup delete a755148bb77721f3e75a0b8eeaf6fe5daf57096e6f7afc9c601209734d227544\n13.141  as               307413 298454   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/9b96b3b3b98b387b-write_buffer_manager.o /tmp/ccchY47w.s\n13.275  containerd-shim  307414 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a755148bb77721f3e75a0b8eeaf6fe5daf57096e6f7afc9c601209734d227544 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a755148bb77721f3e75a0b8eeaf6fe5daf57096e6f7afc9c601209734d2 delete\n13.282  runc             307421 307414   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a755148bb77721f3e75a0b8eeaf6fe5daf57096e6f7afc9c601209734d22754 --log-format json delete --force a755148bb77721f3e75a0b8eeaf6fe5daf57096e6f7afc9c601209734d227544\n13.346  systemd-sysctl   307426 307185   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth13e5aa5 --prefix=/net/ipv4/neigh/veth13e5aa5 --prefix=/net/ipv6/conf/veth13e5aa5 --prefix=/net/ipv6/neigh/veth13e5aa5\n13.428  rustup           307428 301076   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n13.431  riscv64-linux-g  307427 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n13.437  riscv64-linux-g  307437 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n13.441  riscv64-linux-g  307438 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n13.443  cc1plus          307439 307427   0 \n13.446  cc1plus          307440 307437   0 \n13.446  cc1plus          307441 307438   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n13.633  as               307451 306803   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/94ad6eef41e52848-offpeak_time_info.o /tmp/cc5CtDjd.s\n13.660  16               307468 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n13.682  frpc             307468 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n13.832  as               307476 304468   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/94ad6eef41e52848-db_options.o /tmp/ccK4O0xv.s\n13.924  as               307477 305618   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/a357d10ea739bc2c-adaptive_table_factory.o /tmp/ccL43ckf.s\n14.189  as               307478 307397   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/053adb4869b9269c-data_block_hash_index.o /tmp/cc5GAu3s.s\n14.203  as               307479 305026   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/94ad6eef41e52848-options_helper.o /tmp/ccwo695W.s\n14.257  powerpc64le-lin  307480 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n14.264  cc1plus          307481 307480   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n14.449  riscv64-linux-g  307482 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n14.451  riscv64-linux-g  307483 229324   0 \n14.455  cc1plus          307484 307482   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n14.461  cc1plus          307485 307483   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n14.755  riscv64-linux-g  307486 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n14.766  cc1plus          307487 307486   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n14.941  as               307488 306512   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/94ad6eef41e52848-configurable.o /tmp/ccZRosjc.s\n15.286  as               307489 306556   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/94ad6eef41e52848-customizable.o /tmp/ccibq38v.s\n15.631  as               307490 307035   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/053adb4869b9269c-block_prefix_index.o /tmp/cc6jZMBq.s\n15.772  powerpc64le-lin  307491 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n15.776  cc1plus          307493 307491   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n15.794  powerpc64le-lin  307492 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n15.804  cc1plus          307494 307492   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n15.922  as               307495 306195   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-filter_block_reader_common.o /tmp/cc3OYL6b.s\n15.948  as               307496 306681   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-index_reader_common.o /tmp/cc2gQpS0.s\n16.072  as               307497 305631   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/8d9638b5dd27dacb-statistics.o /tmp/ccCYEUpz.s\n16.085  as               307498 305029   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/94ad6eef41e52848-options_parser.o /tmp/ccH43egk.s\n16.166  as               307499 305554   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-block_cache.o /tmp/ccJsEO5J.s\n16.283  riscv64-linux-g  307500 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n16.293  cc1plus          307502 307500   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n16.295  riscv64-linux-g  307501 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n16.303  cc1plus          307503 307501   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n16.426  powerpc64le-lin  307504 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n16.431  cc1plus          307505 307504   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n16.620  riscv64-linux-g  307506 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n16.626  cc1plus          307507 307506   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n16.758  aarch64-linux-g  307508 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n16.763  cc1plus          307510 307508   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n16.763  aarch64-linux-g  307509 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n16.769  cc1plus          307511 307509   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n16.782  aarch64-linux-g  307512 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n16.790  cc1plus          307513 307512   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n16.923  as               307514 305620   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/053adb4869b9269c-binary_search_index_reader. /tmp/cc2T5Ir5.s\n17.235  riscv64-linux-g  307515 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n17.244  cc1plus          307516 307515   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n17.390  as               307517 307427   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/053adb4869b9269c-data_block_footer.o /tmp/ccKR64Mb.s\n17.560  riscv64-linux-g  307518 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n17.567  cc1plus          307519 307518   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n18.090  as               307520 306198   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-flush_block_policy.o /tmp/ccFhNTAt.s\n18.131  as               307521 305787   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/8d9638b5dd27dacb-thread_status_updater_deb /tmp/cc3jgnNm.s\n18.165  as               307522 306136   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/94ad6eef41e52848-cf_options.o /tmp/cc6z5BcL.s\n18.388  as               307523 306922   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/053adb4869b9269c-block_prefetcher.o /tmp/cccWWTBU.s\n18.434  as               307524 306318   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-full_filter_block.o /tmp/cczF3RZv.s\n18.489  runc             307525 300930   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/55015dff9db4fc35415c3e1e329a4cdd0c9f0ade6a99f54d541e36a0531 --log-format json --systemd-cgroup kill --all 55015dff9db4fc35415c3e1e329a4cdd0c9f0ade6a99f54d541e36a0531d827c 9\n18.511  runc             307531 300930   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/55015dff9db4fc35415c3e1e329a4cdd0c9f0ade6a99f54d541e36a0531 --log-format json --systemd-cgroup delete 55015dff9db4fc35415c3e1e329a4cdd0c9f0ade6a99f54d541e36a0531d827c\n18.548  as               307537 306781   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-parsed_full_filter_block.o /tmp/ccVEJdQv.s\n18.583  powerpc64le-lin  307538 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n18.593  cc1plus          307539 307538   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n18.734  containerd-shim  307541 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 55015dff9db4fc35415c3e1e329a4cdd0c9f0ade6a99f54d541e36a0531d827c -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/55015dff9db4fc35415c3e1e329a4cdd0c9f0ade6a99f54d541e36a0531 delete\n18.739  runc             307548 307541   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/55015dff9db4fc35415c3e1e329a4cdd0c9f0ade6a99f54d541e36a0531d827 --log-format json delete --force 55015dff9db4fc35415c3e1e329a4cdd0c9f0ade6a99f54d541e36a0531d827c\n18.785  systemd-sysctl   307554 307553   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetheeaee50 --prefix=/net/ipv4/neigh/vetheeaee50 --prefix=/net/ipv6/conf/vetheeaee50 --prefix=/net/ipv6/neigh/vetheeaee50\n18.909  aarch64-linux-g  307556 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n18.916  cc1plus          307558 307556   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n18.917  aarch64-linux-g  307557 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n18.924  cc1plus          307559 307557   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n19.234  aarch64-linux-g  307560 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n19.245  cc1plus          307561 307560   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n19.315  runc             307562 301257   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9298839e331017280ebb70d2917cb62fa9ffdb09a76a2ae3f0b7fd00897 --log-format json --systemd-cgroup kill --all 9298839e331017280ebb70d2917cb62fa9ffdb09a76a2ae3f0b7fd0089717fc1 9\n19.343  runc             307568 301257   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9298839e331017280ebb70d2917cb62fa9ffdb09a76a2ae3f0b7fd00897 --log-format json --systemd-cgroup delete 9298839e331017280ebb70d2917cb62fa9ffdb09a76a2ae3f0b7fd0089717fc1\n"
    },
    {
      "argv": [
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 305861,
      "build_script_target_dir": "io-uring-ea6b6ff132ca8689",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build",
      "pid": 305861,
      "ppid": 305736,
      "root_cargo_pid": 305736,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/libc-1f865bb516326eef/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 305887,
      "build_script_target_dir": "libc-1f865bb516326eef",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/libc-1f865bb516326eef/build-script-build",
      "pid": 305887,
      "ppid": 305736,
      "root_cargo_pid": 305736,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 305887,
      "build_script_target_dir": "libc-1f865bb516326eef",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 305889,
      "ppid": 305887,
      "root_cargo_pid": 305736,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "io-uring",
      "cwd": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
      "event_id": "bsrun:e40eb6ef14bfe16a:7834fb0e631a74d9:c734c2099efb859a",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
      "out_dir": "/target/debug/build/io-uring-ea6b6ff132ca8689/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
      "success": true,
      "target": null,
      "version": "0.7.9",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-riscv64-xz3o61bt/src/io-uring-0.7.9",
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
      "build_script_root_pid": 305887,
      "build_script_target_dir": "libc-1f865bb516326eef",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 305889,
      "ppid": 305887,
      "root_cargo_pid": 305736,
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
