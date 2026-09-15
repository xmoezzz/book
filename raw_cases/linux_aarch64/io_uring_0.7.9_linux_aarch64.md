# `io-uring` `0.7.9`

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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97",
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
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-304906-1783993814613714286.map",
  "pid": 304906,
  "ppid": 304820,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-304906-1783993814613714286.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
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
  "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "workspace_root": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9"
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
      "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
      "name": "io-uring",
      "version": "0.7.9",
      "manifest_path": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9"
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
    "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "exit_code": 0,
  "kind": "exec",
  "pid": 304906,
  "ppid": 304820,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "event_id": "used:cc:f86dc36384ae5382:388485407351196e:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
  "pid": 304906,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "event_id": "used:cc:f86dc36384ae5382:bd96dd2f6ad7680e:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
  "pid": 304906,
  "sha256": "1fa4bf33d9e6566dfe9562fbd8428b1a5a034afa625255e39d56b2b146db947f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "event_id": "used:cc:f86dc36384ae5382:4022540258a8f34c:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
  "pid": 304906,
  "sha256": "2b3e0b282b63ac4758ac6764b545719de70e66416a19f600eb84cef60e4901b2",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "event_id": "used:cc:f86dc36384ae5382:b9c575d9166d471d:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
  "pid": 304906,
  "sha256": "e7ac3cdc8949e2de6c2f2d5b3fef283eda2664cf8baaab0479bfb626e5e0d691",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "event_id": "used:cc:f86dc36384ae5382:d0d2a84cd5e13f23:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
  "pid": 304906,
  "sha256": "d612c3616e025230c84bbb6e1f9527abf1bb85abc4444ae3abd35d222d87f46a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "event_id": "used:cc:f86dc36384ae5382:5a37bec5af7bdc86:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
  "pid": 304906,
  "sha256": "590547109752b3bd3fed33fb95efd5365e327ce88cd3d4d74eae8d1657c291e7",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "event_id": "used:cc:f86dc36384ae5382:edfeffd24699eabc:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
  "pid": 304906,
  "sha256": "a54c95f24b3630583495cfaca01c2f4fb1fabc33c93ca08e959a03098bd2b670",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "event_id": "used:cc:f86dc36384ae5382:f788bddab42681f6:c2565016d7c99c55",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
  "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
  "pid": 304906,
  "sha256": "19fb2eeea9364d7061347a67eb332563a7bbc8fc2340cd95e11b69ef53605881",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "cargo_pkg_name": "io-uring",
  "cargo_pkg_version": "0.7.9",
  "context_path": "/tmp/native-trace-303660-1783993810072/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-303660-1783993810072/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 304906,
  "ppid": 304820,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97",
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
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
      "kind": "object",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-304906-1783993814613714286.map",
  "pid": 304906,
  "ppid": 304820,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-304906-1783993814613714286.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/raw-dylibs",
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
  "pid": 304947,
  "ppid": 304819,
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
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/raw-dylibs",
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
  "event_id": "used:cc:bf4e8db12c663bbd:cfecba20bb8775b5:c338943aef9d968a",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
  "path": "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
  "pid": 304947,
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
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/raw-dylibs",
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
  "pid": 304947,
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
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/raw-dylibs",
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
  "pid": 304947,
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
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/raw-dylibs",
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
  "pid": 304947,
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
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/raw-dylibs",
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
  "pid": 304947,
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
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/raw-dylibs",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
    "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/raw-dylibs",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/raw-dylibs",
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
  "context_path": "/tmp/native-trace-303660-1783993810072/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-303660-1783993810072/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 304947,
  "ppid": 304819,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/raw-dylibs",
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
    "/target/debug/build/libc-1f865bb516326eef/rustcZQl842",
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
      "directory": "/target/debug/build/libc-1f865bb516326eef/rustcZQl842",
      "kind": "object",
      "path": "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
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
  "map_path": "/tmp/native-trace-link-cc-304947-1783993814763184307.map",
  "pid": 304947,
  "ppid": 304819,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-304947-1783993814763184307.map"
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
  "parsed_event_count": 507,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 508,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "547 --prefix=/net/ipv4/neigh/vethf799547 --prefix=/net/ipv6/conf/vethf799547 --prefix=/net/ipv6/neigh/vethf799547\n14.256  containerd-shim  306708 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id ae3720e9b0af2ee6f6cda48004e665ab0fa40cc9589852296de922c7d29c21c3 start\n14.261  containerd-shim  306716 306708   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id ae3720e9b0af2ee6f6cda48004e665ab0fa40cc9589852296de922c7d29c21c3 -address /var/run/docker/containerd/containerd.sock\n14.266  runc             306726 306716   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ae3720e9b0af2ee6f6cda48004e665ab0fa40cc9589852296de922c7d29 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ae3720e9b0af2ee6f6cda48004e665ab0fa40cc9589852296de922c7d29 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ae3720e9b0af2ee6f6cda48004e665ab0fa40cc9589852296de922c7d29 ae3720e9b0af2ee6f6cda48004e665ab0fa40cc9589852296de922c7d29c21c3\n14.275  exe              306734 306726   0 /proc/self/exe init\n14.334  exe              306741 306726   0 /proc/1599/exe -exec-root=/var/run/docker ae3720e9b0af2ee6f6cda48004e665ab0fa40cc9589852296de922c7d29c21c3 d7da31e8f8e1\n14.386  exe              306749 1599     0 /proc/self/exe /var/run/docker/netns/86b89204c80f all false\n14.449  as               306761 300823   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/9b96b3b3b98b387b-vectorrep.o /tmp/cc3Y9Ni3.s\n14.455  as               306762 301234   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/8d9638b5dd27dacb-thread_status_updater_debug /tmp/ccmjlOhn.s\n14.470  runc             306763 306716   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ae3720e9b0af2ee6f6cda48004e665ab0fa40cc9589852296de922c7d29 --log-format json --systemd-cgroup start ae3720e9b0af2ee6f6cda48004e665ab0fa40cc9589852296de922c7d29c21c3\n14.481  sh               306736 306716   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n14.484  cargo            306769 306736   0 \n14.504  cargo-native-tr  306769 306736   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n14.513  cargo            306770 306769   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n14.536  rustc            306771 306770   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.562  rustc            306773 306770   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.596  as               306777 300822   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/9b96b3b3b98b387b-skiplistrep.o /tmp/cc3eKnkV.s\n14.631  execsnoop        306778 306769   0 /usr/local/bin/execsnoop -t\n14.631  python3          306778 306769   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n14.687  aarch64-linux-g  306781 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n14.695  cc1plus          306782 306781   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n14.763  riscv64-linux-g  306783 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n14.774  riscv64-linux-g  306784 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n14.777  cc1plus          306785 306783   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n14.780  cc1plus          306786 306784   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n15.008  cargo            306787 306455   0 /usr/bin/cargo build --target aarch64-unknown-linux-gnu\n15.030  rustc            306788 306787   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.060  rustc            306795 306787   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.139/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n15.062  rustc            306796 306787   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pkg_config --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.26/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=3b393852d2f0042a ...\n15.126  powerpc64le-lin  306803 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n15.131  cc1plus          306805 306803   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n15.135  powerpc64le-lin  306804 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n15.139  cc1plus          306807 306804   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n15.146  powerpc64le-lin  306806 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n15.150  cc1plus          306810 306806   0 \n15.181  as               306811 305903   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-block_prefix_index.o /tmp/cc7XNo48.s\n15.254  cc               306814 306795   0 /tmp/native-trace-306455-1783993825174/shims/cc -m64 /target/debug/build/libc-d5e24a35c6204c3a/rustc0XHKcZ/symbols.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.0.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.1.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.f2zdzhd5zba24j4jlc52eo9qw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n15.256  cc               306815 306814   0 /usr/bin/cc -m64 /target/debug/build/libc-d5e24a35c6204c3a/rustc0XHKcZ/symbols.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.0.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.1.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.f2zdzhd5zba24j4jlc52eo9qw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n15.263  collect2         306816 306815   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpoInN7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.266  ld.lld           306817 306816   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpoInN7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a ...\n15.268  rust-lld         306817 306816   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpoInN7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.278  as               306818 306051   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-data_block_footer.o /tmp/ccC7mGCk.s\n15.383  build-script-bu  306844 306787   0 /target/debug/build/libc-d5e24a35c6204c3a/build-script-build\n15.391  rustc            306845 306844   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n15.412  rustc            306852 306787   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.139/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n15.429  as               306847 299068   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/8d9638b5dd27dacb-in_memory_stats_history.o /tmp/ccxQ9gIx.s\n15.580  rustc            306858 306787   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"all\", \"dox\", \"dpms\", \"glx\", \"xcursor\", \"xf86vmode\", \"xfixes\", \"xft\", \"xinerama\", \"xinput\", \"xlib\", \"xlib_xc -C metadata=255bbe92912e964c ...\n15.597  cargo            306862 306534   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n15.622  rustc            306863 306862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.687  rustc            306881 306862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\" -C metadata=aa22ffd12b79e588 ...\n15.692  rustc            306887 306862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bitflags --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.6.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\", \"bytemuck\", \"compiler_builtins\", \"core\", \"example_generated\", \"rustc-dep-of-std\", \"serde\", \"std -C metadata=f53e0d85f976bff3 ...\n15.695  rustc            306892 306862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cfg_if --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"rustc-dep-of-std\")) -C metadata=44346b50c4e9393e ...\n15.704  aarch64-linux-g  306898 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n15.723  aarch64-linux-g  306905 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n15.729  cc               306906 306858   0 /tmp/native-trace-306455-1783993825174/shims/cc -m64 /target/debug/build/x11-5b80cb4da447746c/rustce2VMwa/symbols.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.0qpi4mfmdotxvbce65x1xolh5.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.1y5yvu9jfka2c9w6hdajk52mn.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2pgg0dydoon132lopfe3oeztn.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2xh8j4d4a8yjbzwckhvntue0x.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.39j5lffqj7iy9ky93lf4m1dvl.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.3hkihxlli2q3axu4j61quupxj.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.44rz59wt54t9whocyj6tl3sy6.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.4yf6piehmld0y3l6zfsp08p38.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5afi2faxvl1q1vcdkgjl4nd14.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5vhsfxiiyspcnnavjjajlnp0z.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6apyjtfohf32ep2noq6qjeum7.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6iul0kjx749ugjo89pfuv6u0w.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7it1b9op5prid5fjylbt91g33.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7tq31ucs1ym2b1in8e7evpg2l.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8g3fir08766ptuc0avn1jc9o0.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8sze6dttyazzx1z68t3af3lec.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.9axw8cp9299kam4l1cekxkbkl.113ab0r.rcgu.o ...\n15.730  as               306909 305898   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/8d9638b5dd27dacb-thread_status_util.o /tmp/cclc0GwL.s\n15.730  cc1plus          306908 306898   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n15.732  cc1plus          306907 306905   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n15.741  cc               306910 306906   0 /usr/bin/cc -m64 /target/debug/build/x11-5b80cb4da447746c/rustce2VMwa/symbols.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.0qpi4mfmdotxvbce65x1xolh5.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.1y5yvu9jfka2c9w6hdajk52mn.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2pgg0dydoon132lopfe3oeztn.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2xh8j4d4a8yjbzwckhvntue0x.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.39j5lffqj7iy9ky93lf4m1dvl.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.3hkihxlli2q3axu4j61quupxj.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.44rz59wt54t9whocyj6tl3sy6.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.4yf6piehmld0y3l6zfsp08p38.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5afi2faxvl1q1vcdkgjl4nd14.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5vhsfxiiyspcnnavjjajlnp0z.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6apyjtfohf32ep2noq6qjeum7.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6iul0kjx749ugjo89pfuv6u0w.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7it1b9op5prid5fjylbt91g33.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7tq31ucs1ym2b1in8e7evpg2l.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8g3fir08766ptuc0avn1jc9o0.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8sze6dttyazzx1z68t3af3lec.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.9axw8cp9299kam4l1cekxkbkl.113ab0r.rcgu.o ...\n15.746  collect2         306914 306910   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccI7PGKj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.746  rustc            306888 306862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"bindgen\", \"direct-syscall\", \"io_safety\", \"overwrite\", \"sc\")) -C metadata=b06cd33c50fc6e46 ...\n15.749  ld.lld           306916 306914   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccI7PGKj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c ...\n15.752  rust-lld         306916 306914   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccI7PGKj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.812  riscv64-linux-g  306922 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n15.831  cc1plus          306952 306922   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n15.832  cc               306953 306888   0 /tmp/native-trace-306534-1783993825592/shims/cc -m64 /target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n15.834  cc               306954 306953   0 /usr/bin/cc -m64 /target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n15.838  collect2         306955 306954   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccCtzfZB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.843  ld.lld           306956 306955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccCtzfZB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689 ...\n15.851  rust-lld         306956 306955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccCtzfZB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.923  build-script-bu  306975 306787   0 /target/debug/build/x11-5b80cb4da447746c/build-script-build\n15.960  build-script-bu  306978 306862   0 /target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build\n16.021  rustc            306984 306787   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name x11 --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"all\", \"dox\", \"dpms\", \"glx\", \"xcursor\", \"xf86vmode\", \"xfixes\", \"xft\", \"xinerama\", \"xinput\", \"xlib\", \"xlib_xc -C metadata=5080a35008614888 ...\n16.033  aarch64-linux-g  306986 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n16.033  cc               306987 306881   0 /tmp/native-trace-306534-1783993825592/shims/cc -m64 /target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n16.033  cc               306988 306987   0 /usr/bin/cc -m64 /target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n16.038  collect2         306993 306988   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoCyuab.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.042  cc1plus          306992 306986   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n16.173  ld.lld           306994 306993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoCyuab.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef ...\n16.174  rust-lld         306994 306993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoCyuab.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.323  build-script-bu  307012 306862   0 /target/debug/build/libc-1f865bb516326eef/build-script-build\n16.325  rustc            307013 307012   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n16.365  rustc            307018 306862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\" -C metadata=ef50dfd2da3fa8f6 ...\n16.671  powerpc64le-lin  307022 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n16.684  cc1plus          307023 307022   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n16.688  as               307024 304991   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/94ad6eef41e52848-options.o /tmp/ccjnXIu5.s\n16.800  as               307025 305784   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/8d9638b5dd27dacb-thread_status_updater.o /tmp/ccQOJJvb.s\n16.852  rustc            307029 306862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name io_uring --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"bindgen\", \"direct-syscall\", \"io_safety\", \"overwrite\", \"sc\")) -C metadata=24c87ebdb0a15170 ...\n17.286  as               307034 283962   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/3ac6d140080a8125-version_set.o /tmp/ccd22lF6.s\n17.341  riscv64-linux-g  307035 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n17.346  cc1plus          307036 307035   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n17.700  powerpc64le-lin  307065 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n17.710  cc1plus          307066 307065   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n18.117  as               307148 305901   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/8d9638b5dd27dacb-thread_status_util_debug. /tmp/cchgmAWZ.s\n18.141  runc             307149 301343   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee38 --log-format json --systemd-cgroup kill --all 5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee3869795 9\n18.152  as               307155 305768   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-block_prefetcher.o /tmp/cchUWb2U.s\n18.192  runc             307156 301343   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee38 --log-format json --systemd-cgroup delete 5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee3869795\n18.318  powerpc64le-lin  307162 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n18.325  cc1plus          307163 307162   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n18.369  containerd-shim  307164 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee3869795 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee38 delete\n18.374  runc             307171 307164   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee386979 --log-format json delete --force 5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee3869795\n18.433  sh               307179 307176   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth2983a03\n18.435  sed              307181 307179   0 /usr/bin/sed -n s/^driver: //p\n18.435  ethtool          307180 307179   0 /usr/sbin/ethtool -i veth2983a03\n18.450  systemd-sysctl   307184 307176   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2983a03 --prefix=/net/ipv4/neigh/veth2983a03 --prefix=/net/ipv6/conf/veth2983a03 --prefix=/net/ipv6/neigh/veth2983a03\n18.537  rustup           307186 300818   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.752  as               307195 307065   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/1938569c7fa5575d-mmap.o /tmp/ccEKTJ82.s\n18.794  as               307196 301436   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/94ad6eef41e52848-cf_options.o /tmp/cci4aqh1.s\n18.844  cargo            307197 306769   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n18.867  rustc            307198 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.905  rustc            307204 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.139/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n18.910  rustc            307206 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pkg_config --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.26/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=3b393852d2f0042a ...\n18.946  powerpc64le-lin  307213 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n18.952  cc1plus          307214 307213   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n18.998  as               307215 307213   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/1938569c7fa5575d-stack_trace.o /tmp/cc8iHRTd.s\n19.086  powerpc64le-lin  307220 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n19.091  cc               307221 307204   0 /tmp/native-trace-306769-1783993828472/shims/cc -m64 /target/debug/build/libc-d5e24a35c6204c3a/rustcE96TYb/symbols.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.0.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.1.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.f2zdzhd5zba24j4jlc52eo9qw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.094  cc               307223 307221   0 /usr/bin/cc -m64 /target/debug/build/libc-d5e24a35c6204c3a/rustcE96TYb/symbols.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.0.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.1.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.f2zdzhd5zba24j4jlc52eo9qw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.097  cc1plus          307222 307220   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n19.098  collect2         307224 307223   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cceL2jFQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.103  ld.lld           307225 307224   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cceL2jFQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a ...\n19.107  rust-lld         307225 307224   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cceL2jFQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.215  build-script-bu  307245 307197   0 /target/debug/build/libc-d5e24a35c6204c3a/build-script-build\n19.217  rustc            307246 307245   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n19.243  rustc            307250 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.139/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n19.250  as               307252 300174   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/8d9638b5dd27dacb-persistent_stats_history.o /tmp/cccCVpdD.s\n19.435  rustc            307265 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"all\", \"dox\", \"dpms\", \"glx\", \"xcursor\", \"xf86vmode\", \"xfixes\", \"xft\", \"xinerama\", \"xinput\", \"xlib\", \"xlib_xc -C metadata=255bbe92912e964c ...\n19.590  cc               307291 307265   0 /tmp/native-trace-306769-1783993828472/shims/cc -m64 /target/debug/build/x11-5b80cb4da447746c/rustc0FDdz7/symbols.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.0qpi4mfmdotxvbce65x1xolh5.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.1y5yvu9jfka2c9w6hdajk52mn.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2pgg0dydoon132lopfe3oeztn.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2xh8j4d4a8yjbzwckhvntue0x.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.39j5lffqj7iy9ky93lf4m1dvl.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.3hkihxlli2q3axu4j61quupxj.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.44rz59wt54t9whocyj6tl3sy6.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.4yf6piehmld0y3l6zfsp08p38.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5afi2faxvl1q1vcdkgjl4nd14.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5vhsfxiiyspcnnavjjajlnp0z.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6apyjtfohf32ep2noq6qjeum7.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6iul0kjx749ugjo89pfuv6u0w.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7it1b9op5prid5fjylbt91g33.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7tq31ucs1ym2b1in8e7evpg2l.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8g3fir08766ptuc0avn1jc9o0.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8sze6dttyazzx1z68t3af3lec.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.9axw8cp9299kam4l1cekxkbkl.0yidy89.rcgu.o ...\n19.592  cc               307292 307291   0 /usr/bin/cc -m64 /target/debug/build/x11-5b80cb4da447746c/rustc0FDdz7/symbols.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.0qpi4mfmdotxvbce65x1xolh5.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.1y5yvu9jfka2c9w6hdajk52mn.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2pgg0dydoon132lopfe3oeztn.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2xh8j4d4a8yjbzwckhvntue0x.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.39j5lffqj7iy9ky93lf4m1dvl.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.3hkihxlli2q3axu4j61quupxj.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.44rz59wt54t9whocyj6tl3sy6.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.4yf6piehmld0y3l6zfsp08p38.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5afi2faxvl1q1vcdkgjl4nd14.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5vhsfxiiyspcnnavjjajlnp0z.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6apyjtfohf32ep2noq6qjeum7.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6iul0kjx749ugjo89pfuv6u0w.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7it1b9op5prid5fjylbt91g33.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7tq31ucs1ym2b1in8e7evpg2l.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8g3fir08766ptuc0avn1jc9o0.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8sze6dttyazzx1z68t3af3lec.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.9axw8cp9299kam4l1cekxkbkl.0yidy89.rcgu.o ...\n19.596  collect2         307293 307292   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwSdjuu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.601  ld.lld           307294 307293   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwSdjuu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c ...\n19.605  rust-lld         307294 307293   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwSdjuu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.649  aarch64-linux-g  307311 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n19.660  cc1plus          307312 307311   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n19.712  runc             307314 301759   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ceb9e0963e26c3db3021b259eb93edf9c88ec5ccc3f2c9e953edecf3991 --log-format json --systemd-cgroup kill --all ceb9e0963e26c3db3021b259eb93edf9c88ec5ccc3f2c9e953edecf3991c551b 9\n19.724  build-script-bu  307321 307197   0 /target/debug/build/x11-5b80cb4da447746c/build-script-build\n19.732  rustc            307325 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name x11 --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"all\", \"dox\", \"dpms\", \"glx\", \"xcursor\", \"xf86vmode\", \"xfixes\", \"xft\", \"xinerama\", \"xinput\", \"xlib\", \"xlib_xc -C metadata=795ab2a413e3bdba ...\n19.742  runc             307327 301759   0 \n"
}
```

#### Record 25

```json
{
  "argv": [
    "/target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 304964,
  "build_script_target_dir": "io-uring-ea6b6ff132ca8689",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build",
  "pid": 304964,
  "ppid": 304802,
  "root_cargo_pid": 304802,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
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
  "build_script_root_pid": 305011,
  "build_script_target_dir": "libc-1f865bb516326eef",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/libc-1f865bb516326eef/build-script-build",
  "pid": 305011,
  "ppid": 304802,
  "root_cargo_pid": 304802,
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
    "/usr/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 305011,
  "build_script_target_dir": "libc-1f865bb516326eef",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/usr/bin/rustc",
  "pid": 305012,
  "ppid": 305011,
  "root_cargo_pid": 304802,
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
  "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "event_id": "bsrun:584d900d839a1a80:7834fb0e631a74d9:c734c2099efb859a",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
  "out_dir": "/target/debug/build/io-uring-ea6b6ff132ca8689/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
  "success": true,
  "target": null,
  "version": "0.7.9",
  "_owner": {
    "crate": "io-uring",
    "version": "0.7.9",
    "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
    "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
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
    "/usr/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 305011,
  "build_script_target_dir": "libc-1f865bb516326eef",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/usr/bin/rustc",
  "pid": 305012,
  "ppid": 305011,
  "root_cargo_pid": 304802,
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
  "time": "2026-07-14T01:50:39.249108+00:00",
  "crate": "io-uring",
  "version": "0.7.9",
  "architecture": "aarch64",
  "duration_seconds": 33.94995860895142,
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
        "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
        "manifest_path": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9/Cargo.toml"
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
      "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
      "workspace_root": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9"
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
          "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
          "name": "io-uring",
          "version": "0.7.9",
          "manifest_path": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9"
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
        "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
      "exit_code": 0,
      "kind": "exec",
      "pid": 304906,
      "ppid": 304820,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
      "event_id": "used:cc:f86dc36384ae5382:388485407351196e:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
      "pid": 304906,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
      "event_id": "used:cc:f86dc36384ae5382:bd96dd2f6ad7680e:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
      "pid": 304906,
      "sha256": "1fa4bf33d9e6566dfe9562fbd8428b1a5a034afa625255e39d56b2b146db947f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
      "event_id": "used:cc:f86dc36384ae5382:4022540258a8f34c:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
      "pid": 304906,
      "sha256": "2b3e0b282b63ac4758ac6764b545719de70e66416a19f600eb84cef60e4901b2",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
      "event_id": "used:cc:f86dc36384ae5382:b9c575d9166d471d:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
      "pid": 304906,
      "sha256": "e7ac3cdc8949e2de6c2f2d5b3fef283eda2664cf8baaab0479bfb626e5e0d691",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
      "event_id": "used:cc:f86dc36384ae5382:d0d2a84cd5e13f23:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
      "pid": 304906,
      "sha256": "d612c3616e025230c84bbb6e1f9527abf1bb85abc4444ae3abd35d222d87f46a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
      "event_id": "used:cc:f86dc36384ae5382:5a37bec5af7bdc86:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
      "pid": 304906,
      "sha256": "590547109752b3bd3fed33fb95efd5365e327ce88cd3d4d74eae8d1657c291e7",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
      "event_id": "used:cc:f86dc36384ae5382:edfeffd24699eabc:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
      "pid": 304906,
      "sha256": "a54c95f24b3630583495cfaca01c2f4fb1fabc33c93ca08e959a03098bd2b670",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
      "event_id": "used:cc:f86dc36384ae5382:f788bddab42681f6:c2565016d7c99c55",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689",
      "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
      "pid": 304906,
      "sha256": "19fb2eeea9364d7061347a67eb332563a7bbc8fc2340cd95e11b69ef53605881",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
      "cargo_pkg_name": "io-uring",
      "cargo_pkg_version": "0.7.9",
      "context_path": "/tmp/native-trace-303660-1783993810072/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-303660-1783993810072/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 304906,
      "ppid": 304820,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97",
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
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/rustcafZW97/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.0hdhpyq.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.0hdhpyq.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.0hdhpyq.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.0hdhpyq.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.0hdhpyq.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.0hdhpyq.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/io-uring-ea6b6ff132ca8689",
          "kind": "object",
          "path": "/target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.0hdhpyq.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-304906-1783993814613714286.map",
      "pid": 304906,
      "ppid": 304820,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-304906-1783993814613714286.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/raw-dylibs",
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
      "pid": 304947,
      "ppid": 304819,
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
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/raw-dylibs",
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
      "event_id": "used:cc:bf4e8db12c663bbd:cfecba20bb8775b5:c338943aef9d968a",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef",
      "path": "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
      "pid": 304947,
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
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/raw-dylibs",
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
      "pid": 304947,
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
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/raw-dylibs",
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
      "pid": 304947,
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
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/raw-dylibs",
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
      "pid": 304947,
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
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/raw-dylibs",
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
      "pid": 304947,
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
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/raw-dylibs",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o",
        "/target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/raw-dylibs",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/raw-dylibs",
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
      "context_path": "/tmp/native-trace-303660-1783993810072/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-303660-1783993810072/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 304947,
      "ppid": 304819,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/raw-dylibs",
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
        "/target/debug/build/libc-1f865bb516326eef/rustcZQl842",
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
          "directory": "/target/debug/build/libc-1f865bb516326eef/rustcZQl842",
          "kind": "object",
          "path": "/target/debug/build/libc-1f865bb516326eef/rustcZQl842/symbols.o",
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
      "map_path": "/tmp/native-trace-link-cc-304947-1783993814763184307.map",
      "pid": 304947,
      "ppid": 304819,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-304947-1783993814763184307.map"
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
      "parsed_event_count": 507,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 508,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "547 --prefix=/net/ipv4/neigh/vethf799547 --prefix=/net/ipv6/conf/vethf799547 --prefix=/net/ipv6/neigh/vethf799547\n14.256  containerd-shim  306708 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id ae3720e9b0af2ee6f6cda48004e665ab0fa40cc9589852296de922c7d29c21c3 start\n14.261  containerd-shim  306716 306708   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id ae3720e9b0af2ee6f6cda48004e665ab0fa40cc9589852296de922c7d29c21c3 -address /var/run/docker/containerd/containerd.sock\n14.266  runc             306726 306716   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ae3720e9b0af2ee6f6cda48004e665ab0fa40cc9589852296de922c7d29 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ae3720e9b0af2ee6f6cda48004e665ab0fa40cc9589852296de922c7d29 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ae3720e9b0af2ee6f6cda48004e665ab0fa40cc9589852296de922c7d29 ae3720e9b0af2ee6f6cda48004e665ab0fa40cc9589852296de922c7d29c21c3\n14.275  exe              306734 306726   0 /proc/self/exe init\n14.334  exe              306741 306726   0 /proc/1599/exe -exec-root=/var/run/docker ae3720e9b0af2ee6f6cda48004e665ab0fa40cc9589852296de922c7d29c21c3 d7da31e8f8e1\n14.386  exe              306749 1599     0 /proc/self/exe /var/run/docker/netns/86b89204c80f all false\n14.449  as               306761 300823   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/9b96b3b3b98b387b-vectorrep.o /tmp/cc3Y9Ni3.s\n14.455  as               306762 301234   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/8d9638b5dd27dacb-thread_status_updater_debug /tmp/ccmjlOhn.s\n14.470  runc             306763 306716   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ae3720e9b0af2ee6f6cda48004e665ab0fa40cc9589852296de922c7d29 --log-format json --systemd-cgroup start ae3720e9b0af2ee6f6cda48004e665ab0fa40cc9589852296de922c7d29c21c3\n14.481  sh               306736 306716   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n14.484  cargo            306769 306736   0 \n14.504  cargo-native-tr  306769 306736   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n14.513  cargo            306770 306769   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n14.536  rustc            306771 306770   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.562  rustc            306773 306770   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.596  as               306777 300822   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/9b96b3b3b98b387b-skiplistrep.o /tmp/cc3eKnkV.s\n14.631  execsnoop        306778 306769   0 /usr/local/bin/execsnoop -t\n14.631  python3          306778 306769   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n14.687  aarch64-linux-g  306781 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n14.695  cc1plus          306782 306781   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n14.763  riscv64-linux-g  306783 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n14.774  riscv64-linux-g  306784 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n14.777  cc1plus          306785 306783   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n14.780  cc1plus          306786 306784   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n15.008  cargo            306787 306455   0 /usr/bin/cargo build --target aarch64-unknown-linux-gnu\n15.030  rustc            306788 306787   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.060  rustc            306795 306787   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.139/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n15.062  rustc            306796 306787   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pkg_config --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.26/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=3b393852d2f0042a ...\n15.126  powerpc64le-lin  306803 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n15.131  cc1plus          306805 306803   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n15.135  powerpc64le-lin  306804 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n15.139  cc1plus          306807 306804   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n15.146  powerpc64le-lin  306806 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n15.150  cc1plus          306810 306806   0 \n15.181  as               306811 305903   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-block_prefix_index.o /tmp/cc7XNo48.s\n15.254  cc               306814 306795   0 /tmp/native-trace-306455-1783993825174/shims/cc -m64 /target/debug/build/libc-d5e24a35c6204c3a/rustc0XHKcZ/symbols.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.0.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.1.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.f2zdzhd5zba24j4jlc52eo9qw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n15.256  cc               306815 306814   0 /usr/bin/cc -m64 /target/debug/build/libc-d5e24a35c6204c3a/rustc0XHKcZ/symbols.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.0.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.1.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.f2zdzhd5zba24j4jlc52eo9qw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n15.263  collect2         306816 306815   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpoInN7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.266  ld.lld           306817 306816   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpoInN7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a ...\n15.268  rust-lld         306817 306816   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpoInN7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.278  as               306818 306051   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-data_block_footer.o /tmp/ccC7mGCk.s\n15.383  build-script-bu  306844 306787   0 /target/debug/build/libc-d5e24a35c6204c3a/build-script-build\n15.391  rustc            306845 306844   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n15.412  rustc            306852 306787   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.139/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n15.429  as               306847 299068   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/8d9638b5dd27dacb-in_memory_stats_history.o /tmp/ccxQ9gIx.s\n15.580  rustc            306858 306787   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"all\", \"dox\", \"dpms\", \"glx\", \"xcursor\", \"xf86vmode\", \"xfixes\", \"xft\", \"xinerama\", \"xinput\", \"xlib\", \"xlib_xc -C metadata=255bbe92912e964c ...\n15.597  cargo            306862 306534   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n15.622  rustc            306863 306862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.687  rustc            306881 306862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\" -C metadata=aa22ffd12b79e588 ...\n15.692  rustc            306887 306862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bitflags --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.6.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\", \"bytemuck\", \"compiler_builtins\", \"core\", \"example_generated\", \"rustc-dep-of-std\", \"serde\", \"std -C metadata=f53e0d85f976bff3 ...\n15.695  rustc            306892 306862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cfg_if --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"rustc-dep-of-std\")) -C metadata=44346b50c4e9393e ...\n15.704  aarch64-linux-g  306898 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n15.723  aarch64-linux-g  306905 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n15.729  cc               306906 306858   0 /tmp/native-trace-306455-1783993825174/shims/cc -m64 /target/debug/build/x11-5b80cb4da447746c/rustce2VMwa/symbols.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.0qpi4mfmdotxvbce65x1xolh5.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.1y5yvu9jfka2c9w6hdajk52mn.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2pgg0dydoon132lopfe3oeztn.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2xh8j4d4a8yjbzwckhvntue0x.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.39j5lffqj7iy9ky93lf4m1dvl.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.3hkihxlli2q3axu4j61quupxj.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.44rz59wt54t9whocyj6tl3sy6.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.4yf6piehmld0y3l6zfsp08p38.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5afi2faxvl1q1vcdkgjl4nd14.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5vhsfxiiyspcnnavjjajlnp0z.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6apyjtfohf32ep2noq6qjeum7.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6iul0kjx749ugjo89pfuv6u0w.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7it1b9op5prid5fjylbt91g33.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7tq31ucs1ym2b1in8e7evpg2l.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8g3fir08766ptuc0avn1jc9o0.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8sze6dttyazzx1z68t3af3lec.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.9axw8cp9299kam4l1cekxkbkl.113ab0r.rcgu.o ...\n15.730  as               306909 305898   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/8d9638b5dd27dacb-thread_status_util.o /tmp/cclc0GwL.s\n15.730  cc1plus          306908 306898   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n15.732  cc1plus          306907 306905   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n15.741  cc               306910 306906   0 /usr/bin/cc -m64 /target/debug/build/x11-5b80cb4da447746c/rustce2VMwa/symbols.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.0qpi4mfmdotxvbce65x1xolh5.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.1y5yvu9jfka2c9w6hdajk52mn.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2pgg0dydoon132lopfe3oeztn.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2xh8j4d4a8yjbzwckhvntue0x.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.39j5lffqj7iy9ky93lf4m1dvl.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.3hkihxlli2q3axu4j61quupxj.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.44rz59wt54t9whocyj6tl3sy6.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.4yf6piehmld0y3l6zfsp08p38.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5afi2faxvl1q1vcdkgjl4nd14.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5vhsfxiiyspcnnavjjajlnp0z.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6apyjtfohf32ep2noq6qjeum7.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6iul0kjx749ugjo89pfuv6u0w.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7it1b9op5prid5fjylbt91g33.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7tq31ucs1ym2b1in8e7evpg2l.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8g3fir08766ptuc0avn1jc9o0.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8sze6dttyazzx1z68t3af3lec.113ab0r.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.9axw8cp9299kam4l1cekxkbkl.113ab0r.rcgu.o ...\n15.746  collect2         306914 306910   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccI7PGKj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.746  rustc            306888 306862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"bindgen\", \"direct-syscall\", \"io_safety\", \"overwrite\", \"sc\")) -C metadata=b06cd33c50fc6e46 ...\n15.749  ld.lld           306916 306914   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccI7PGKj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c ...\n15.752  rust-lld         306916 306914   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccI7PGKj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.812  riscv64-linux-g  306922 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n15.831  cc1plus          306952 306922   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n15.832  cc               306953 306888   0 /tmp/native-trace-306534-1783993825592/shims/cc -m64 /target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n15.834  cc               306954 306953   0 /usr/bin/cc -m64 /target/debug/build/io-uring-ea6b6ff132ca8689/rustcWV4eVu/symbols.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.0171du4u1uhasq8tgpr8wpijx.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.2pemxd3g7u5i0qfodjfz6v798.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.3drw9p5dolzkwhvqaiwcnvexy.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.78mlhris7s76gkuzbwv18e6mh.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.9qoer1tlx8713smbfajgk0eq9.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.ckqzy9wiz0wc4d5oafb5midu3.1w8q73h.rcgu.o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689.b8j816opurmt9opi17loxv3ny.1w8q73h.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n15.838  collect2         306955 306954   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccCtzfZB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.843  ld.lld           306956 306955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccCtzfZB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/io-uring-ea6b6ff132ca8689/build_script_build-ea6b6ff132ca8689 ...\n15.851  rust-lld         306956 306955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccCtzfZB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.923  build-script-bu  306975 306787   0 /target/debug/build/x11-5b80cb4da447746c/build-script-build\n15.960  build-script-bu  306978 306862   0 /target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build\n16.021  rustc            306984 306787   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name x11 --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"all\", \"dox\", \"dpms\", \"glx\", \"xcursor\", \"xf86vmode\", \"xfixes\", \"xft\", \"xinerama\", \"xinput\", \"xlib\", \"xlib_xc -C metadata=5080a35008614888 ...\n16.033  aarch64-linux-g  306986 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n16.033  cc               306987 306881   0 /tmp/native-trace-306534-1783993825592/shims/cc -m64 /target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n16.033  cc               306988 306987   0 /usr/bin/cc -m64 /target/debug/build/libc-1f865bb516326eef/rustcPbKuZN/symbols.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.0.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.1.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.build_script_build.c85179e7c2b17248-cgu.2.rcgu.o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef.cimf0kll639oy0cviqcr3fvwz.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n16.038  collect2         306993 306988   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoCyuab.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.042  cc1plus          306992 306986   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n16.173  ld.lld           306994 306993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoCyuab.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-1f865bb516326eef/build_script_build-1f865bb516326eef ...\n16.174  rust-lld         306994 306993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoCyuab.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.323  build-script-bu  307012 306862   0 /target/debug/build/libc-1f865bb516326eef/build-script-build\n16.325  rustc            307013 307012   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n16.365  rustc            307018 306862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.156/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\" -C metadata=ef50dfd2da3fa8f6 ...\n16.671  powerpc64le-lin  307022 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n16.684  cc1plus          307023 307022   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n16.688  as               307024 304991   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/94ad6eef41e52848-options.o /tmp/ccjnXIu5.s\n16.800  as               307025 305784   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/8d9638b5dd27dacb-thread_status_updater.o /tmp/ccQOJJvb.s\n16.852  rustc            307029 306862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name io_uring --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"bindgen\", \"direct-syscall\", \"io_safety\", \"overwrite\", \"sc\")) -C metadata=24c87ebdb0a15170 ...\n17.286  as               307034 283962   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/3ac6d140080a8125-version_set.o /tmp/ccd22lF6.s\n17.341  riscv64-linux-g  307035 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n17.346  cc1plus          307036 307035   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n17.700  powerpc64le-lin  307065 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n17.710  cc1plus          307066 307065   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n18.117  as               307148 305901   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/8d9638b5dd27dacb-thread_status_util_debug. /tmp/cchgmAWZ.s\n18.141  runc             307149 301343   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee38 --log-format json --systemd-cgroup kill --all 5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee3869795 9\n18.152  as               307155 305768   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/053adb4869b9269c-block_prefetcher.o /tmp/cchUWb2U.s\n18.192  runc             307156 301343   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee38 --log-format json --systemd-cgroup delete 5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee3869795\n18.318  powerpc64le-lin  307162 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n18.325  cc1plus          307163 307162   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n18.369  containerd-shim  307164 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee3869795 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee38 delete\n18.374  runc             307171 307164   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee386979 --log-format json delete --force 5cd4f0b229b9f4d9d9e7defa332a6ff89b64c8c7ae19f6ea03ea05bee3869795\n18.433  sh               307179 307176   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth2983a03\n18.435  sed              307181 307179   0 /usr/bin/sed -n s/^driver: //p\n18.435  ethtool          307180 307179   0 /usr/sbin/ethtool -i veth2983a03\n18.450  systemd-sysctl   307184 307176   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2983a03 --prefix=/net/ipv4/neigh/veth2983a03 --prefix=/net/ipv6/conf/veth2983a03 --prefix=/net/ipv6/neigh/veth2983a03\n18.537  rustup           307186 300818   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.752  as               307195 307065   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/1938569c7fa5575d-mmap.o /tmp/ccEKTJ82.s\n18.794  as               307196 301436   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/94ad6eef41e52848-cf_options.o /tmp/cci4aqh1.s\n18.844  cargo            307197 306769   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n18.867  rustc            307198 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.905  rustc            307204 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.139/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n18.910  rustc            307206 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pkg_config --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.26/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=3b393852d2f0042a ...\n18.946  powerpc64le-lin  307213 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n18.952  cc1plus          307214 307213   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n18.998  as               307215 307213   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/1938569c7fa5575d-stack_trace.o /tmp/cc8iHRTd.s\n19.086  powerpc64le-lin  307220 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n19.091  cc               307221 307204   0 /tmp/native-trace-306769-1783993828472/shims/cc -m64 /target/debug/build/libc-d5e24a35c6204c3a/rustcE96TYb/symbols.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.0.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.1.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.f2zdzhd5zba24j4jlc52eo9qw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.094  cc               307223 307221   0 /usr/bin/cc -m64 /target/debug/build/libc-d5e24a35c6204c3a/rustcE96TYb/symbols.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.0.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.build_script_build.b2fccbced73dd4b3-cgu.1.rcgu.o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a.f2zdzhd5zba24j4jlc52eo9qw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.097  cc1plus          307222 307220   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n19.098  collect2         307224 307223   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cceL2jFQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.103  ld.lld           307225 307224   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cceL2jFQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-d5e24a35c6204c3a/build_script_build-d5e24a35c6204c3a ...\n19.107  rust-lld         307225 307224   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cceL2jFQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.215  build-script-bu  307245 307197   0 /target/debug/build/libc-d5e24a35c6204c3a/build-script-build\n19.217  rustc            307246 307245   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n19.243  rustc            307250 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.139/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n19.250  as               307252 300174   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/8d9638b5dd27dacb-persistent_stats_history.o /tmp/cccCVpdD.s\n19.435  rustc            307265 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"all\", \"dox\", \"dpms\", \"glx\", \"xcursor\", \"xf86vmode\", \"xfixes\", \"xft\", \"xinerama\", \"xinput\", \"xlib\", \"xlib_xc -C metadata=255bbe92912e964c ...\n19.590  cc               307291 307265   0 /tmp/native-trace-306769-1783993828472/shims/cc -m64 /target/debug/build/x11-5b80cb4da447746c/rustc0FDdz7/symbols.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.0qpi4mfmdotxvbce65x1xolh5.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.1y5yvu9jfka2c9w6hdajk52mn.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2pgg0dydoon132lopfe3oeztn.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2xh8j4d4a8yjbzwckhvntue0x.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.39j5lffqj7iy9ky93lf4m1dvl.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.3hkihxlli2q3axu4j61quupxj.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.44rz59wt54t9whocyj6tl3sy6.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.4yf6piehmld0y3l6zfsp08p38.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5afi2faxvl1q1vcdkgjl4nd14.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5vhsfxiiyspcnnavjjajlnp0z.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6apyjtfohf32ep2noq6qjeum7.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6iul0kjx749ugjo89pfuv6u0w.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7it1b9op5prid5fjylbt91g33.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7tq31ucs1ym2b1in8e7evpg2l.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8g3fir08766ptuc0avn1jc9o0.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8sze6dttyazzx1z68t3af3lec.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.9axw8cp9299kam4l1cekxkbkl.0yidy89.rcgu.o ...\n19.592  cc               307292 307291   0 /usr/bin/cc -m64 /target/debug/build/x11-5b80cb4da447746c/rustc0FDdz7/symbols.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.0qpi4mfmdotxvbce65x1xolh5.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.1y5yvu9jfka2c9w6hdajk52mn.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2pgg0dydoon132lopfe3oeztn.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.2xh8j4d4a8yjbzwckhvntue0x.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.39j5lffqj7iy9ky93lf4m1dvl.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.3hkihxlli2q3axu4j61quupxj.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.44rz59wt54t9whocyj6tl3sy6.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.4yf6piehmld0y3l6zfsp08p38.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5afi2faxvl1q1vcdkgjl4nd14.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.5vhsfxiiyspcnnavjjajlnp0z.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6apyjtfohf32ep2noq6qjeum7.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.6iul0kjx749ugjo89pfuv6u0w.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7it1b9op5prid5fjylbt91g33.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.7tq31ucs1ym2b1in8e7evpg2l.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8g3fir08766ptuc0avn1jc9o0.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.8sze6dttyazzx1z68t3af3lec.0yidy89.rcgu.o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c.9axw8cp9299kam4l1cekxkbkl.0yidy89.rcgu.o ...\n19.596  collect2         307293 307292   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwSdjuu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.601  ld.lld           307294 307293   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwSdjuu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/x11-5b80cb4da447746c/build_script_build-5b80cb4da447746c ...\n19.605  rust-lld         307294 307293   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwSdjuu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.649  aarch64-linux-g  307311 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n19.660  cc1plus          307312 307311   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n19.712  runc             307314 301759   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ceb9e0963e26c3db3021b259eb93edf9c88ec5ccc3f2c9e953edecf3991 --log-format json --systemd-cgroup kill --all ceb9e0963e26c3db3021b259eb93edf9c88ec5ccc3f2c9e953edecf3991c551b 9\n19.724  build-script-bu  307321 307197   0 /target/debug/build/x11-5b80cb4da447746c/build-script-build\n19.732  rustc            307325 307197   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name x11 --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"all\", \"dox\", \"dpms\", \"glx\", \"xcursor\", \"xf86vmode\", \"xfixes\", \"xft\", \"xinerama\", \"xinput\", \"xlib\", \"xlib_xc -C metadata=795ab2a413e3bdba ...\n19.742  runc             307327 301759   0 \n"
    },
    {
      "argv": [
        "/target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 304964,
      "build_script_target_dir": "io-uring-ea6b6ff132ca8689",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build",
      "pid": 304964,
      "ppid": 304802,
      "root_cargo_pid": 304802,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/libc-1f865bb516326eef/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 305011,
      "build_script_target_dir": "libc-1f865bb516326eef",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/libc-1f865bb516326eef/build-script-build",
      "pid": 305011,
      "ppid": 304802,
      "root_cargo_pid": 304802,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 305011,
      "build_script_target_dir": "libc-1f865bb516326eef",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/usr/bin/rustc",
      "pid": 305012,
      "ppid": 305011,
      "root_cargo_pid": 304802,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "io-uring",
      "cwd": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
      "event_id": "bsrun:584d900d839a1a80:7834fb0e631a74d9:c734c2099efb859a",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/io-uring-ea6b6ff132ca8689/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
      "out_dir": "/target/debug/build/io-uring-ea6b6ff132ca8689/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
      "success": true,
      "target": null,
      "version": "0.7.9",
      "_owner": {
        "crate": "io-uring",
        "version": "0.7.9",
        "package_id": "path+file:///tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9#io-uring@0.7.9",
        "manifest_dir": "/tmp/crate-build-aarch64-z3_28rbm/src/io-uring-0.7.9",
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
        "/usr/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 305011,
      "build_script_target_dir": "libc-1f865bb516326eef",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/usr/bin/rustc",
      "pid": 305012,
      "ppid": 305011,
      "root_cargo_pid": 304802,
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
