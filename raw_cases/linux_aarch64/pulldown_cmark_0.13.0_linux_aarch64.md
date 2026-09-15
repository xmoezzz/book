# `pulldown-cmark` `0.13.0`

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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
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
  "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
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
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-228142-1783993322758653098.map",
  "pid": 228142,
  "ppid": 228091,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-228142-1783993322758653098.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
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
  "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "workspace_root": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bincode@1.3.3",
      "name": "bincode",
      "version": "1.3.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bincode-1.3.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bincode-1.3.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.8.0",
      "name": "bitflags",
      "version": "2.8.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.8.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.8.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#getopts@0.2.21",
      "name": "getopts",
      "version": "0.2.21",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getopts-0.2.21/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getopts-0.2.21"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.14",
      "name": "itoa",
      "version": "1.0.14",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.14/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.14"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.5.0",
      "name": "lazy_static",
      "version": "1.5.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.4",
      "name": "memchr",
      "version": "2.7.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.93",
      "name": "proc-macro2",
      "version": "1.0.93",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.93/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.93"
    },
    {
      "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
      "name": "pulldown-cmark",
      "version": "0.13.0",
      "manifest_path": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#pulldown-cmark-escape@0.11.0",
      "name": "pulldown-cmark-escape",
      "version": "0.11.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pulldown-cmark-escape-0.11.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pulldown-cmark-escape-0.11.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.38",
      "name": "quote",
      "version": "1.0.38",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.38/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.38"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.11.1",
      "name": "regex",
      "version": "1.11.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.11.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.11.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.9",
      "name": "regex-automata",
      "version": "0.4.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.5",
      "name": "regex-syntax",
      "version": "0.8.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.19",
      "name": "ryu",
      "version": "1.0.19",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.19/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.19"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
      "name": "serde",
      "version": "1.0.217",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.217",
      "name": "serde_derive",
      "version": "1.0.217",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.217/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.217"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.138",
      "name": "serde_json",
      "version": "1.0.138",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.138/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.138"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.98",
      "name": "syn",
      "version": "2.0.98",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.98/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.98"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicase@2.8.1",
      "name": "unicase",
      "version": "2.8.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicase-2.8.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicase-2.8.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.16",
      "name": "unicode-ident",
      "version": "1.0.16",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.16/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.16"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-width@0.1.14",
      "name": "unicode-width",
      "version": "0.1.14",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14"
    }
  ],
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 228142,
  "ppid": 228091,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "pulldown-cmark",
  "cargo_pkg_version": "0.13.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "event_id": "used:cc:d3ac5204f681dcf4:e8a4799b0f5d0f16:154f8437eefadc83",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
  "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
  "pid": 228142,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "pulldown-cmark",
  "cargo_pkg_version": "0.13.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "event_id": "used:cc:d3ac5204f681dcf4:8cd8d3290d576469:154f8437eefadc83",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
  "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
  "pid": 228142,
  "sha256": "c2861dfc0730066307330bdd8f09329a25fb1401787317d8d6f84e07a79367be",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "pulldown-cmark",
  "cargo_pkg_version": "0.13.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "event_id": "used:cc:d3ac5204f681dcf4:c0634259666a5771:154f8437eefadc83",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
  "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
  "pid": 228142,
  "sha256": "110338b05bbde1028400fd58ac3f0e28e09357b32787f9fd095a070f23b57af1",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "pulldown-cmark",
  "cargo_pkg_version": "0.13.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "event_id": "used:cc:d3ac5204f681dcf4:d9e0421f1b5c4a71:154f8437eefadc83",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
  "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
  "pid": 228142,
  "sha256": "89b7b0b159803ad1bfa752554bcb58e1b266f29ec22d4d3b69124b8a04913598",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "pulldown-cmark",
  "cargo_pkg_version": "0.13.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "event_id": "used:cc:d3ac5204f681dcf4:918575cdc225bded:154f8437eefadc83",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
  "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
  "pid": 228142,
  "sha256": "d15ff9a3c18aa57495ceebac0a1fffaebb70933e00305025e9aab0089c3b8b6c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "pulldown-cmark",
  "cargo_pkg_version": "0.13.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "event_id": "used:cc:d3ac5204f681dcf4:43176d72d9f34ec7:154f8437eefadc83",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
  "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
  "pid": 228142,
  "sha256": "f9b5d0c0ac001426656778c6f16b9b758e8e0dead4138fecb51571ef80fc08fd",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "pulldown-cmark",
  "cargo_pkg_version": "0.13.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "event_id": "used:cc:d3ac5204f681dcf4:f76ec5133e23174c:154f8437eefadc83",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
  "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
  "pid": 228142,
  "sha256": "a4914eb4d43ad45db892635f72dd262e44cb35a20e5a76b2a5ff53c9a3de75b6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
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
  "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "cargo_pkg_name": "pulldown-cmark",
  "cargo_pkg_version": "0.13.0",
  "context_path": "/tmp/native-trace-227057-1783993318826/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-227057-1783993318826/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 228142,
  "ppid": 228091,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
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
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-228142-1783993322758653098.map",
  "pid": 228142,
  "ppid": 228091,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-228142-1783993322758653098.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 13

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

#### Record 14

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 1,
  "parsed_event_count": 1170,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1171,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "nu/bin/rustc -vV\n17.737  rustc            231047 230681   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.738  rustc            231047 230681   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.754  docker           231059 230597   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.755  docker           231065 230681   0 /usr/bin/docker --help\n17.765  rustc            231074 230770   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.766  rustc            231076 230716   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.771  rustc            231080 230815   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.776  rustc            231097 230593   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.779  rustc            231076 230716   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.783  rustc            231080 230815   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.788  rustc            231097 230593   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.803  docker           231122 230681   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.803  docker           231131 230815   0 /usr/bin/docker --help\n17.803  docker           231130 230716   0 /usr/bin/docker --help\n17.803  rustc            231074 230770   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.811  docker           231150 230770   0 /usr/bin/docker --help\n17.812  docker           231157 230593   0 /usr/bin/docker --help\n17.820  runc             231168 1599     0 /usr/bin/runc --version\n17.821  docker           231169 230716   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.824  docker-init      231176 1599     0 /usr/bin/docker-init --version\n17.826  docker           231186 230681   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.828  docker           231189 230815   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.840  docker           231203 230593   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.843  docker           231206 230770   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.849  runc             231217 1599     0 /usr/bin/runc --version\n17.851  runc             231218 1599     0 /usr/bin/runc --version\n17.859  runc             231233 1599     0 /usr/bin/runc --version\n17.859  docker-init      231232 1599     0 /usr/bin/docker-init --version\n17.863  docker-init      231241 1599     0 /usr/bin/docker-init --version\n17.864  runc             231242 1599     0 /usr/bin/runc --version\n17.869  docker-init      231249 1599     0 /usr/bin/docker-init --version\n17.870  docker           231250 230593   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.875  runc             231257 1599     0 /usr/bin/runc --version\n17.879  docker           231263 230716   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.881  docker-init      231264 1599     0 /usr/bin/docker-init --version\n17.885  docker-init      231272 1599     0 /usr/bin/docker-init --version\n17.893  docker           231273 230770   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.897  runc             231283 1599     0 /usr/bin/runc --version\n17.901  docker           231289 230815   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.907  docker-init      231296 1599     0 /usr/bin/docker-init --version\n17.910  runc             231297 1599     0 /usr/bin/runc --version\n17.914  runc             231304 1599     0 /usr/bin/runc --version\n17.941  powerpc64le-lin  231312 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n17.943  powerpc64le-lin  231313 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n17.947  cc1plus          231314 231313   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n17.959  cc1plus          231315 231312   0 \n17.963  rustup           231316 230593   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.963  rustup           231317 230681   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.964  docker-init      231318 1599     0 /usr/bin/docker-init --version\n17.972  rustup           231337 230593   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.972  runc             231335 1599     0 \n17.972  rustup           231338 230681   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.996  systemd-sysctl   231364 231355   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethdd37870 --prefix=/net/ipv4/neigh/vethdd37870 --prefix=/net/ipv6/conf/vethdd37870 --prefix=/net/ipv6/neigh/vethdd37870\n17.996  systemd-sysctl   231358 231356   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethee811d7 --prefix=/net/ipv4/neigh/vethee811d7 --prefix=/net/ipv6/conf/vethee811d7 --prefix=/net/ipv6/neigh/vethee811d7\n18.001  docker-init      231336 1599     0 /usr/bin/docker-init --version\n18.001  rustup           231365 230716   0 /home/xmoe/.cargo/bin/rustup toolchain list\n18.002  docker-init      231366 1599     0 /usr/bin/docker-init --version\n18.014  rustup           231380 230716   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n18.017  rustup           231377 230681   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.047  containerd-shim  231423 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e721041d49 start\n18.049  uname            231427 230681   0 /usr/bin/uname -r\n18.049  rustup           231428 230815   0 /home/xmoe/.cargo/bin/rustup toolchain list\n18.052  containerd-shim  231433 231423   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e721041d49 -address /var/run/docker/containerd/containerd.sock\n18.057  runc             231451 231433   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e7210 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e7210 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e7210 9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e721041d49\n18.059  rustup           231455 230815   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n18.062  powerpc64le-lin  231459 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n18.065  cc1plus          231469 231459   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n18.067  rustup           231470 230716   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.070  exe              231471 231451   0 /proc/self/exe init\n18.097  rustup           231482 230815   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.107  uname            231492 230716   0 /usr/bin/uname -r\n18.116  docker           231493 230681   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n18.133  rustup           231502 230770   0 /home/xmoe/.cargo/bin/rustup toolchain list\n18.138  docker           231516 230716   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n18.143  rustup           231522 230770   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n18.174  exe              231531 231451   0 /proc/1599/exe -exec-root=/var/run/docker 9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e721041d49 d7da31e8f8e1\n18.192  rustup           231543 230770   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.213  systemd-sysctl   231555 231401   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth9934856 --prefix=/net/ipv4/neigh/veth9934856 --prefix=/net/ipv6/conf/veth9934856 --prefix=/net/ipv6/neigh/veth9934856\n18.217  systemd-sysctl   231556 231414   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe119a28 --prefix=/net/ipv4/neigh/vethe119a28 --prefix=/net/ipv6/conf/vethe119a28 --prefix=/net/ipv6/neigh/vethe119a28\n18.226  exe              231557 1599     0 /proc/self/exe /var/run/docker/netns/3891ca36ee5d all false\n18.247  containerd-shim  231568 1663     0 \n18.252  containerd-shim  231574 231568   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 50baf8ba78f50747c45965feaea935725c9479f26e775a94aa494e77e8b912b8 -address /var/run/docker/containerd/containerd.sock\n18.264  runc             231587 231574   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/50baf8ba78f50747c45965feaea935725c9479f26e775a94aa494e77e8b --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/50baf8ba78f50747c45965feaea935725c9479f26e775a94aa494e77e8b --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/50baf8ba78f50747c45965feaea935725c9479f26e775a94aa494e77e8b 50baf8ba78f50747c45965feaea935725c9479f26e775a94aa494e77e8b912b8\n18.279  exe              231595 231587   0 /proc/self/exe init\n18.323  rustup           231597 230593   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.331  uname            231606 230770   0 /usr/bin/uname -r\n18.331  uname            231607 230815   0 /usr/bin/uname -r\n18.374  docker           231608 230770   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n18.387  systemd-sysctl   231620 231567   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb266392 --prefix=/net/ipv4/neigh/vethb266392 --prefix=/net/ipv6/conf/vethb266392 --prefix=/net/ipv6/neigh/vethb266392\n18.390  systemd-sysctl   231615 231405   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethda7c6d7 --prefix=/net/ipv4/neigh/vethda7c6d7 --prefix=/net/ipv6/conf/vethda7c6d7 --prefix=/net/ipv6/neigh/vethda7c6d7\n18.414  uname            231626 230593   0 /usr/bin/uname -r\n18.425  containerd-shim  231627 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c036fbb start\n18.435  containerd-shim  231634 231627   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c036fbb -address /var/run/docker/containerd/containerd.sock\n18.439  runc             231644 231433   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e7210 --log-format json --systemd-cgroup start 9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e721041d49\n18.439  runc             231645 231634   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c0 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c0 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c0 c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c036fbb\n18.447  docker           231656 230815   0 \n18.447  docker           231657 230593   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n18.449  sh               231483 231433   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n18.454  cargo            231668 231483   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n18.456  exe              231681 231645   0 /proc/self/exe init\n18.469  rustc            231682 230948   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.477  rustc            231683 230543   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n18.488  exe              231694 231587   0 /proc/1599/exe -exec-root=/var/run/docker 50baf8ba78f50747c45965feaea935725c9479f26e775a94aa494e77e8b912b8 d7da31e8f8e1\n18.496  cargo-native-tr  231668 231483   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n18.497  systemd-sysctl   231703 231401   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf838d78 --prefix=/net/ipv4/neigh/vethf838d78 --prefix=/net/ipv6/conf/vethf838d78 --prefix=/net/ipv6/neigh/vethf838d78\n18.497  systemd-sysctl   231702 231414   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth27f8c07 --prefix=/net/ipv4/neigh/veth27f8c07 --prefix=/net/ipv6/conf/veth27f8c07 --prefix=/net/ipv6/neigh/veth27f8c07\n18.497  rustc            231683 230543   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n18.531  cargo            231708 231668   0 \n18.538  exe              231737 1599     0 /proc/self/exe /var/run/docker/netns/5a373f7d76a3 all false\n18.538  rustc            231725 231708   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.538  docker           231726 230543   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n18.538  docker           231714 230543   0 /usr/bin/docker --help\n18.538  containerd-shim  231728 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 005a30947f53fcdc8ab0c974bf80257173816e3f63a4d05fe559ab13628a213f start\n18.538  rustc            231724 230949   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.540  containerd-shim  231742 231728   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 005a30947f53fcdc8ab0c974bf80257173816e3f63a4d05fe559ab13628a213f -address /var/run/docker/containerd/containerd.sock\n18.554  runc             231759 1599     0 /usr/bin/runc --version\n18.560  docker-init      231767 1599     0 /usr/bin/docker-init --version\n18.569  docker           231769 230543   0 /usr/bin/docker info -f {{.SecurityOptions}}\n18.576  runc             231776 231742   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/005a30947f53fcdc8ab0c974bf80257173816e3f63a4d05fe559ab13628 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/005a30947f53fcdc8ab0c974bf80257173816e3f63a4d05fe559ab13628 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/005a30947f53fcdc8ab0c974bf80257173816e3f63a4d05fe559ab13628 005a30947f53fcdc8ab0c974bf80257173816e3f63a4d05fe559ab13628a213f\n18.583  exe              231786 231776   0 /proc/self/exe init\n18.585  exe              231788 231645   0 /proc/1599/exe   \n18.588  rustc            231789 231708   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n18.594  runc             231797 1599     0 /usr/bin/runc --version\n18.598  systemd-sysctl   231803 231401   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth21e9547 --prefix=/net/ipv4/neigh/veth21e9547 --prefix=/net/ipv6/conf/veth21e9547 --prefix=/net/ipv6/neigh/veth21e9547\n18.601  docker-init      231807 1599     0 /usr/bin/docker-init --version\n18.626  rustc            231810 230875   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n18.645  rustc            231819 230871   0 \n18.645  rustc            231810 230875   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n18.645  rustup           231829 230543   0 \n18.645  exe              231831 1599     0 /proc/self/exe /var/run/docker/netns/ff1f3950e33e all false\n18.646  rustc            231819 230871   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n18.652  docker           231847 230875   0 /usr/bin/docker --help\n18.653  rustup           231848 230543   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n18.655  systemd-sysctl   231849 231414   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc710035 --prefix=/net/ipv4/neigh/vethc710035 --prefix=/net/ipv6/conf/vethc710035 --prefix=/net/ipv6/neigh/vethc710035\n18.656  systemd-sysctl   231854 231420   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethed0b790 --prefix=/net/ipv4/neigh/vethed0b790 --prefix=/net/ipv6/conf/vethed0b790 --prefix=/net/ipv6/neigh/vethed0b790\n18.657  systemd-sysctl   231857 231406   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethedc8fc4 --prefix=/net/ipv4/neigh/vethedc8fc4 --prefix=/net/ipv6/conf/vethedc8fc4 --prefix=/net/ipv6/neigh/vethedc8fc4\n18.692  execsnoop        231881 231668   0 /usr/local/bin/execsnoop -t\n18.692  containerd-shim  231895 231855   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c60f58a -address /var/run/docker/containerd/containerd.sock\n18.692  docker           231906 230875   0 \n18.692  runc             231910 231895   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c6 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c6 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c6 84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c60f58a\n18.692  docker           231917 230871   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n18.692  containerd-shim  231855 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c60f58a start\n18.692  docker           231880 230871   0 \n18.692  python3          231881 231668   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n18.696  runc             231928 231574   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/50baf8ba78f50747c45965feaea935725c9479f26e775a94aa494e77e8b --log-format json --systemd-cgroup start 50baf8ba78f50747c45965feaea935725c9479f26e775a94aa494e77e8b912b8\n18.696  rustup           231927 230543   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.698  exe              231936 231910   0 /proc/self/exe init\n18.705  sh               231614 231574   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n18.707  cargo            231948 231614   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n18.717  runc             231949 1599     0 /usr/bin/runc --version\n18.717  exe              231950 231776   0 /proc/1599/exe -exec-root=/var/run/docker 005a30947f53fcdc8ab0c974bf80257173816e3f63a4d05fe559ab13628a213f d7da31e8f8e1\n18.726  docker-init      231962 1599     0 /usr/bin/docker-init --version\n18.728  cargo-native-tr  231948 231614   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n18.730  docker           231963 230871   0 /usr/bin/docker info -f {{.SecurityOptions}}\n18.736  runc             231970 1599     0 /usr/bin/runc --version\n18.736  cargo            231965 231948   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n18.737  uname            231972 230543   0 /usr/bin/uname -r\n18.754  runc             231977 1599     0 /usr/bin/runc --version\n18.754  rustc            231978 231965   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.790  docker           231995 230875   0 \n18.790  exe              231989 1599     0 /proc/self/exe /var/run/docker/netns/2d4bafcda6bd all false\n18.790  docker-init      231990 1599     0 /usr/bin/docker-init --version\n18.792  docker           232007 230543   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n18.797  cargo            232015 230411   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n18.799  docker-init      232019 1599     0 /usr/bin/docker-init --version\n18.800  rustc            232018 231965   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n18.832  rustc            232023 232015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.854  runc             232028 1599     0 /usr/bin/runc --version\n18.859  containerd-shim  232034 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a2d3a3cebe327f99386114c35bd96bc6147822d9863d0bc9494f42fe893a0b85 start\n18.860  docker-init      232035 1599     0 /usr/bin/docker-init --version\n18.871  containerd-shim  232047 232034   0 \n18.878  rustup           232056 230871   0 /home/xmoe/.cargo/bin/rustup toolchain list\n18.884  runc             232057 232047   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a2d3a3cebe327f99386114c35bd96bc6147822d9863d0bc9494f42fe893 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a2d3a3cebe327f99386114c35bd96bc6147822d9863d0bc9494f42fe893 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a2d3a3cebe327f99386114c35bd96bc6147822d9863d0bc9494f42fe893 a2d3a3cebe327f99386114c35bd96bc6147822d9863d0bc9494f42fe893a0b85\n18.896  rustup           232073 230871   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n18.897  rustup           232074 230875   0 /home/xmoe/.cargo/bin/rustup toolchain list\n18.910  exe              232072 232057   0 \n18.911  rustup           232091 230875   0 \n18.939  execsnoop        232102 231948   0 /usr/local/bin/execsnoop -t\n18.941  python3          232102 231948   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n18.949  rustc            232103 232015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_width --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"cjk\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n18.955  rustup           232110 230875   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.977  rustc            232119 232015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name memchr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n18.978  rustc            232120 232015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pulldown_cmark_escape --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pulldown-cmark-escape-0.11.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"simd\")) -C metadata=4bd53abb8701dcef ...\n18.978  rustc            232125 232015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bitflags --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.8.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\", \"bytemuck\", \"compiler_builtins\", \"core\", \"example_generated\", \"rustc-dep-of-std\", \"serde\", \"std -C metadata=2c953780ec993778 ...\n18.978  rustc            232117 232015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicase --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicase-2.8.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"nightly\")) -C metadata=029785130794bfe3 ...\n18.979  rustc            232130 232015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --cfg feature=\"default\" --cfg feature=\"getopts\" --cfg ...\n18.997  runc             232148 231742   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/005a30947f53fcdc8ab0c974bf80257173816e3f63a4d05fe559ab13628 --log-format json --systemd-cgroup start 005a30947f53fcdc8ab0c974bf80257173816e3f63a4d05fe559ab13628a213f\n19.003  exe              232155 231910   0 /proc/1599/exe -exec-root=/var/run/docker 84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c60f58a d7da31e8f8e1\n19.009  sh               231834 231742   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n19.011  cargo            232163 231834   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n19.023  systemd-sysctl   232168 231414   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethffd302e --prefix=/net/ipv4/neigh/vethffd302e --prefix=/net/ipv6/conf/vethffd302e --prefix=/net/ipv6/neigh/vethffd302e\n19.023  uname            232169 230875   0 /usr/bin/uname -r\n19.024  systemd-sysctl   232167 231401   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf4dab3c --prefix=/net/ipv4/neigh/vethf4dab3c --prefix=/net/ipv6/conf/vethf4dab3c --prefix=/net/ipv6/neigh/vethf4dab3c\n19.041  cargo-native-tr  232163 231834   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n19.043  rustup           232179 230871   0 \n19.047  exe              232181 232057   0 /proc/1599/exe -exec-root=/var/run/docker a2d3a3cebe327f99386114c35bd96bc6147822d9863d0bc9494f42fe893a0b85 d7da31e8f8e1\n19.047  cargo            232180 232163   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n19.059  cargo            232187 230445   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n19.067  exe              232197 1599     0 /proc/self/exe /var/run/docker/netns/963e751319cc all false\n19.070  docker           232198 230875   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n19.079  rustc            232210 232180   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.090  rustc            232215 232187   0 \n19.094  exe              232221 1599     0 \n19.096  rustc            232223 232180   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n19.117  uname            232245 230871   0 /usr/bin/uname -r\n19.133  containerd-shim  232249 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a13797654060bc617eadbdf2de9a0ddd5064c7336e66cdae32473a70c9a6f758 start\n19.138  containerd-shim  232256 232249   0 \n19.145  cc               232258 232130   0 /tmp/native-trace-230411-1783993336672/shims/cc -m64 /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n19.145  execsnoop        232269 232163   0 /usr/local/bin/execsnoop -t\n19.145  runc             232270 232256   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a13797654060bc617eadbdf2de9a0ddd5064c7336e66cdae32473a70c9a --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a13797654060bc617eadbdf2de9a0ddd5064c7336e66cdae32473a70c9a --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a13797654060bc617eadbdf2de9a0ddd5064c7336e66cdae32473a70c9a a13797654060bc617eadbdf2de9a0ddd5064c7336e66cdae32473a70c9a6f758\n19.146  python3          232269 232163   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n19.146  docker           232272 230871   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n19.148  cc               232278 232258   0 /usr/bin/cc -m64 /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n19.150  rustc            232282 232187   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bitflags --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.8.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\", \"bytemuck\", \"compiler_builtins\", \"core\", \"example_generated\", \"rustc-dep-of-std\", \"serde\", \"std -C metadata=36881999aa281e81 ...\n19.155  rustc            232292 232187   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_width --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"cjk\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n19.158  rustc            232274 232187   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --cfg feature=\"default\" --cfg feature=\"getopts\" --cfg ...\n19.163  rustc            232301 232187   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicase --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicase-2.8.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"nightly\")) -C metadata=2c88d6915fd715d2 ...\n19.163  rustc            232294 232187   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name memchr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n19.164  rustc            232296 232187   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pulldown_cmark_escape --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pulldown-cmark-escape-0.11.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"simd\")) -C metadata=3860ee446f168590 ...\n19.165  collect2         232293 232278   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfeM0YZ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.167  ld.lld           232304 232293   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfeM0YZ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a ...\n19.173  rust-lld         232304 232293   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfeM0YZ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.178  runc             232248 231634   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c0 --log-format json --systemd-cgroup start c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c036fbb\n19.194  sh               231699 231634   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n19.200  cargo            232333 231699   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n19.209  runc             232338 231895   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c6 --log-format json --systemd-cgroup start 84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c60f58a\n19.219  sh               232106 231895   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n19.219  exe              232303 232270   0 /proc/self/exe init\n19.225  cargo            232350 232106   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n19.242  cargo-native-tr  232333 231699   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n19.251  cargo            232356 232333   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n19.257  cargo-native-tr  232350 232106   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n19.267  cargo            232362 232350   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n19.313  rustc            232366 232356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.313  build-script-bu  232365 232015   0 \n19.314  systemd-sysctl   232381 231401   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth519ed85 --prefix=/net/ipv4/neigh/veth519ed85 --prefix=/net/ipv6/conf/veth519ed85 --prefix=/net/ipv6/neigh/veth519ed85\n19.314  systemd-sysctl   232379 231414   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethafd3855 --prefix=/net/ipv4/neigh/vethafd3855 --prefix=/net/ipv6/conf/vethafd3855 --prefix=/net/ipv6/neigh/vethafd3855\n19.397  rustc            232392 232356   0 \n19.397  rustc            232390 232362   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.397  cargo            232395 232133   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n19.397  cargo-native-tr  232395 232133   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n19.397  containerd-shim  232405 1663     0 \n19.397  execsnoop        232409 232333   0 /usr/local/bin/execsnoop -t\n19.397  python3          232409 232333   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n19.397  containerd-shim  232416 232405   0 \n19.397  runc             232441 232416   0 \n19.397  sh               232133 232047   0 \n19.397  systemd-sysctl   232399 231356   0 \n19.397  runc             232384 232047   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a2d3a3cebe327f99386114c35bd96bc6147822d9863d0bc9494f42fe893 --log-format json --systemd-cgroup start a2d3a3cebe327f99386114c35bd96bc6147822d9863d0bc9494f42fe893a0b85\n19.399  cargo            232417 232395   0 \n19.399  execsnoop        232418 232350   0 \n19.399  python3          232418 232350   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n19.399  as               232419 229482   0 \n19.399  containerd-shim  232429 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 8f7a7bd94d562343c07279149835aba7e953de145eeeddef49adf64892df7984 start\n19.399  containerd-shim  232442 232429   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 8f7a7bd94d562343c07279149835aba7e953de145eeeddef49adf64892df7984 -address /var/run/docker/containerd/containerd.sock\n19.399  runc             232459 232442   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8f7a7bd94d562343c07279149835aba7e953de145eeeddef49adf64892d --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8f7a7bd94d562343c07279149835aba7e953de145eeeddef49adf64892d --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8f7a7bd94d562343c07279149835aba7e953de145eeeddef49adf64892d 8f7a7bd94d562343c07279149835aba7e953de145eeeddef49adf64892df7984\n19.399  rustc            232396 232362   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n19.399  systemd-sysctl   232398 231420   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd9e0e2a --prefix=/net/ipv4/neigh/vethd9e0e2a --prefix=/net/ipv6/conf/vethd9e0e2a --prefix=/net/ipv6/neigh/vethd9e0e2a\n19.401  exe              232464 232441   0 /proc/self/exe init\n19.405  exe              232470 232459   0 /proc/self/exe init\n19.408  rustc            232468 232187   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name getopts --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getopts-0.2.21/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"core\", \"rustc-dep-of-std\", \"std\")) -C metadata=3ae2bfa83c9fd852 ...\n19.415  rustc            232473 232417   0 /usr/bin/rustc -vV\n19.431  rustc            232476 232417   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n19.471  execsnoop        232480 232395   0 /usr/local/bin/execsnoop -t\n19.471  python3          232480 232395   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n19.502  exe              232496 232270   0 /proc/1599/exe -exec-root=/var/run/docker a13797654060bc617eadbdf2de9a0ddd5064c7336e66cdae32473a70c9a6f758 d7da31e8f8e1\n19.507  rustc            232498 232015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name getopts --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getopts-0.2.21/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"core\", \"rustc-dep-of-std\", \"std\")) -C metadata=cc848890360245b1 ...\n19.508  cc               232467 232274   0 /tmp/native-trace-230445-1783993336797/shims/cc -m64 /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcdpHTIq/symbols.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.0pjbxil.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.0pjbxil.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.0pjbxil.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.0pjbxil.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.0pjbxil.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.0pjbxil.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n19.535  cc               232511 232467   0 /usr/bin/cc -m64 /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcdpHTIq/symbols.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.0pjbxil.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.0pjbxil.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.0pjbxil.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.0pjbxil.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.0pjbxil.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.0pjbxil.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n19.546  collect2         232514 232511   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cconuQpV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.548  exe              232516 1599     0 /proc/self/exe /var/run/docker/netns/f2da248364f8 all false\n19.555  ld.lld           232517 232514   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cconuQpV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a ...\n19.558  rust-lld         232517 232514   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cconuQpV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.564  exe              232527 232441   0 \n19.566  exe              232528 232459   0 /proc/1599/exe -exec-root=/var/run/docker 8f7a7bd94d562343c07279149835aba7e953de145eeeddef49adf64892df7984 d7da31e8f8e1\n19.607  exe              232564 1599     0 /proc/self/exe /var/run/docker/netns/059c170244a1 all false\n19.610  exe              232565 1599     0 /proc/self/exe /var/run/docker/netns/c54fb9590b1c all false\n19.675  runc             232585 232256   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a13797654060bc617eadbdf2de9a0ddd5064c7336e66cdae32473a70c9a --log-format json --systemd-cgroup start a13797654060bc617eadbdf2de9a0ddd5064c7336e66cdae32473a70c9a6f758\n19.685  sh               232358 232256   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n19.687  cargo            232591 232358   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n19.709  runc             232592 232416   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aec7b5f96dc6125e3c9d623e698cbb9a005a2a228f21fa301b39dfe20fb --log-format json --systemd-cgroup start aec7b5f96dc6125e3c9d623e698cbb9a005a2a228f21fa301b39dfe20fbb451e\n19.719  cargo-native-tr  232591 232358   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n19.723  sh               232486 232416   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n19.731  cargo            232603 232591   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n19.732  cargo            232600 232486   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n19.732  build-script-bu  232605 232187   0 /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build-script-build\n19.752  cargo-native-tr  232600 232486   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n19.760  as               232607 230504   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/644b6a24ae2ff5c1-blob_file_garbage.o /tmp/ccYD0lOQ.s\n19.765  cargo            232609 232600   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n19.769  rustc            232613 232015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pulldown_cmark --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --cfg feature=\"default\" --cfg feature=\"getopts\" --cfg ...\n19.791  rustc            232614 232603   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.818  rustc            232621 232603   0 \n19.823  rustc            232623 232609   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.873  rustc            232629 232609   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n19.913  as               232633 229542   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/40a8ecc0aa07be2f-secondary_cache.o /tmp/ccPCEfwl.s\n19.922  execsnoop        232639 232591   0 /usr/local/bin/execsnoop -t\n19.922  python3          232639 232591   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n19.939  runc             232619 232442   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8f7a7bd94d562343c07279149835aba7e953de145eeeddef49adf64892d --log-format json --systemd-cgroup start 8f7a7bd94d562343c07279149835aba7e953de145eeeddef49adf64892df7984\n19.953  sh               232497 232442   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n19.953  cargo            232648 232497   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n19.972  execsnoop        232649 232600   0 /usr/local/bin/execsnoop -t\n19.972  python3          232649 232600   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n19.996  cargo-native-tr  232648 232497   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n20.007  cargo            232652 232648   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n20.064  rustc            232653 232652   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.101  rustc            232656 232652   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.217  powerpc64le-lin  232661 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n20.229  cc1plus          232663 232661   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n20.233  execsnoop        232660 232648   0 /usr/local/bin/execsnoop -t\n20.235  python3          232660 232648   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n20.261  powerpc64le-lin  232662 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n20.270  cc1plus          232666 232662   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n20.502  riscv64-linux-g  232671 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n20.508  cc1plus          232673 232671   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n20.608  rustc            232679 232187   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pulldown_cmark --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --cfg feature=\"default\" --cfg feature=\"getopts\" --cfg ...\n20.913  sh               232684 2147557   0 /bin/sh -c which ps\n20.914  which            232684 2147557   0 /usr/bin/which ps\n20.918  sh               232685 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n20.920  ps               232685 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n20.982  sh               232686 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n20.984  cpuUsage.sh      232686 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n20.987  sed              232687 232686   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n20.990  cat              232688 232686   0 /usr/bin/cat /proc/2240539/stat\n20.994  cat              232689 232686   0 /usr/bin/cat /proc/4193716/stat\n20.997  sleep            232690 232686   0 /usr/bin/sleep 1\n"
}
```

#### Record 15

```json
{
  "argv": [
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 228177,
  "build_script_target_dir": "pulldown-cmark-3bfaa0284ef6cd6a",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build-script-build",
  "pid": 228177,
  "ppid": 228064,
  "root_cargo_pid": 228064,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "_build_script_out_dir": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/out"
}
```

#### Record 16

```json
{
  "crate": "pulldown-cmark",
  "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "event_id": "bsrun:dcc79535ed866cb1:7a6292397c2722f9:45329bbb65dbee50",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
  "out_dir": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
  "success": true,
  "target": null,
  "version": "0.13.0",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
    "source": "cwd_prefix"
  }
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T01:42:23.818133+00:00",
  "crate": "pulldown-cmark",
  "version": "0.13.0",
  "architecture": "aarch64",
  "duration_seconds": 29.297655388712883,
  "trace_record_count": 16,
  "trace_owner_summary": {
    "owner_package_count": 22,
    "owner_packages": [
      {
        "crate": "pulldown-cmark-escape",
        "version": "0.11.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#pulldown-cmark-escape@0.11.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pulldown-cmark-escape-0.11.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pulldown-cmark-escape-0.11.0/Cargo.toml"
      },
      {
        "crate": "regex-automata",
        "version": "0.4.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.9/Cargo.toml"
      },
      {
        "crate": "serde_derive",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.217",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.217",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.217/Cargo.toml"
      },
      {
        "crate": "unicode-ident",
        "version": "1.0.16",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.16",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.16",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.16/Cargo.toml"
      },
      {
        "crate": "unicode-width",
        "version": "0.1.14",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-width@0.1.14",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14/Cargo.toml"
      },
      {
        "crate": "aho-corasick",
        "version": "1.1.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.3/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.93",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.93",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.93",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.93/Cargo.toml"
      },
      {
        "crate": "regex-syntax",
        "version": "0.8.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.5/Cargo.toml"
      },
      {
        "crate": "serde_json",
        "version": "1.0.138",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.138",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.138",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.138/Cargo.toml"
      },
      {
        "crate": "lazy_static",
        "version": "1.5.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.5.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0/Cargo.toml"
      },
      {
        "crate": "bitflags",
        "version": "2.8.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.8.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.8.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.8.0/Cargo.toml"
      },
      {
        "crate": "getopts",
        "version": "0.2.21",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#getopts@0.2.21",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getopts-0.2.21",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getopts-0.2.21/Cargo.toml"
      },
      {
        "crate": "bincode",
        "version": "1.3.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bincode@1.3.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bincode-1.3.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bincode-1.3.3/Cargo.toml"
      },
      {
        "crate": "serde",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217/Cargo.toml"
      },
      {
        "crate": "unicase",
        "version": "2.8.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicase@2.8.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicase-2.8.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicase-2.8.1/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "2.7.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4/Cargo.toml"
      },
      {
        "crate": "quote",
        "version": "1.0.38",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.38",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.38",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.38/Cargo.toml"
      },
      {
        "crate": "regex",
        "version": "1.11.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.11.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.11.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.11.1/Cargo.toml"
      },
      {
        "crate": "itoa",
        "version": "1.0.14",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.14",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.14",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.14/Cargo.toml"
      },
      {
        "crate": "ryu",
        "version": "1.0.19",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.19",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.19",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.19/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "2.0.98",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.98",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.98",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.98/Cargo.toml"
      },
      {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
        "manifest_path": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0/Cargo.toml"
      }
    ],
    "attributed_event_count": 13,
    "unattributed_event_count": 3,
    "owners": [
      {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
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
      }
    ]
  },
  "trace_records": [
    {
      "event": "native_trace_root_context",
      "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
      "workspace_root": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bincode@1.3.3",
          "name": "bincode",
          "version": "1.3.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bincode-1.3.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bincode-1.3.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.8.0",
          "name": "bitflags",
          "version": "2.8.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.8.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.8.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#getopts@0.2.21",
          "name": "getopts",
          "version": "0.2.21",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getopts-0.2.21/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getopts-0.2.21"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.14",
          "name": "itoa",
          "version": "1.0.14",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.14/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.14"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.5.0",
          "name": "lazy_static",
          "version": "1.5.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.4",
          "name": "memchr",
          "version": "2.7.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.93",
          "name": "proc-macro2",
          "version": "1.0.93",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.93/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.93"
        },
        {
          "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
          "name": "pulldown-cmark",
          "version": "0.13.0",
          "manifest_path": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#pulldown-cmark-escape@0.11.0",
          "name": "pulldown-cmark-escape",
          "version": "0.11.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pulldown-cmark-escape-0.11.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pulldown-cmark-escape-0.11.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.38",
          "name": "quote",
          "version": "1.0.38",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.38/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.38"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.11.1",
          "name": "regex",
          "version": "1.11.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.11.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.11.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.9",
          "name": "regex-automata",
          "version": "0.4.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.5",
          "name": "regex-syntax",
          "version": "0.8.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.19",
          "name": "ryu",
          "version": "1.0.19",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.19/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.19"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
          "name": "serde",
          "version": "1.0.217",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.217",
          "name": "serde_derive",
          "version": "1.0.217",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.217/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.217"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.138",
          "name": "serde_json",
          "version": "1.0.138",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.138/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.138"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.98",
          "name": "syn",
          "version": "2.0.98",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.98/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.98"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicase@2.8.1",
          "name": "unicase",
          "version": "2.8.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicase-2.8.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicase-2.8.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.16",
          "name": "unicode-ident",
          "version": "1.0.16",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.16/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.16"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-width@0.1.14",
          "name": "unicode-width",
          "version": "0.1.14",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14"
        }
      ],
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 228142,
      "ppid": 228091,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "pulldown-cmark",
      "cargo_pkg_version": "0.13.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
      "event_id": "used:cc:d3ac5204f681dcf4:e8a4799b0f5d0f16:154f8437eefadc83",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
      "pid": 228142,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "pulldown-cmark",
      "cargo_pkg_version": "0.13.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
      "event_id": "used:cc:d3ac5204f681dcf4:8cd8d3290d576469:154f8437eefadc83",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
      "pid": 228142,
      "sha256": "c2861dfc0730066307330bdd8f09329a25fb1401787317d8d6f84e07a79367be",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "pulldown-cmark",
      "cargo_pkg_version": "0.13.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
      "event_id": "used:cc:d3ac5204f681dcf4:c0634259666a5771:154f8437eefadc83",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
      "pid": 228142,
      "sha256": "110338b05bbde1028400fd58ac3f0e28e09357b32787f9fd095a070f23b57af1",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "pulldown-cmark",
      "cargo_pkg_version": "0.13.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
      "event_id": "used:cc:d3ac5204f681dcf4:d9e0421f1b5c4a71:154f8437eefadc83",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
      "pid": 228142,
      "sha256": "89b7b0b159803ad1bfa752554bcb58e1b266f29ec22d4d3b69124b8a04913598",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "pulldown-cmark",
      "cargo_pkg_version": "0.13.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
      "event_id": "used:cc:d3ac5204f681dcf4:918575cdc225bded:154f8437eefadc83",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
      "pid": 228142,
      "sha256": "d15ff9a3c18aa57495ceebac0a1fffaebb70933e00305025e9aab0089c3b8b6c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "pulldown-cmark",
      "cargo_pkg_version": "0.13.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
      "event_id": "used:cc:d3ac5204f681dcf4:43176d72d9f34ec7:154f8437eefadc83",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
      "pid": 228142,
      "sha256": "f9b5d0c0ac001426656778c6f16b9b758e8e0dead4138fecb51571ef80fc08fd",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "pulldown-cmark",
      "cargo_pkg_version": "0.13.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
      "event_id": "used:cc:d3ac5204f681dcf4:f76ec5133e23174c:154f8437eefadc83",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
      "pid": 228142,
      "sha256": "a4914eb4d43ad45db892635f72dd262e44cb35a20e5a76b2a5ff53c9a3de75b6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
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
      "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
      "cargo_pkg_name": "pulldown-cmark",
      "cargo_pkg_version": "0.13.0",
      "context_path": "/tmp/native-trace-227057-1783993318826/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-227057-1783993318826/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 228142,
      "ppid": 228091,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
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
          "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo",
          "kind": "object",
          "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcOLSUdo/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
          "kind": "object",
          "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.00qqmtw.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
          "kind": "object",
          "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.00qqmtw.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
          "kind": "object",
          "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.00qqmtw.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
          "kind": "object",
          "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.00qqmtw.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
          "kind": "object",
          "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.00qqmtw.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
          "kind": "object",
          "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.00qqmtw.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-228142-1783993322758653098.map",
      "pid": 228142,
      "ppid": 228091,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-228142-1783993322758653098.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
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
      "parsed_event_count": 1170,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1171,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "nu/bin/rustc -vV\n17.737  rustc            231047 230681   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.738  rustc            231047 230681   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.754  docker           231059 230597   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.755  docker           231065 230681   0 /usr/bin/docker --help\n17.765  rustc            231074 230770   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.766  rustc            231076 230716   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.771  rustc            231080 230815   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.776  rustc            231097 230593   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.779  rustc            231076 230716   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.783  rustc            231080 230815   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.788  rustc            231097 230593   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.803  docker           231122 230681   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.803  docker           231131 230815   0 /usr/bin/docker --help\n17.803  docker           231130 230716   0 /usr/bin/docker --help\n17.803  rustc            231074 230770   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.811  docker           231150 230770   0 /usr/bin/docker --help\n17.812  docker           231157 230593   0 /usr/bin/docker --help\n17.820  runc             231168 1599     0 /usr/bin/runc --version\n17.821  docker           231169 230716   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.824  docker-init      231176 1599     0 /usr/bin/docker-init --version\n17.826  docker           231186 230681   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.828  docker           231189 230815   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.840  docker           231203 230593   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.843  docker           231206 230770   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.849  runc             231217 1599     0 /usr/bin/runc --version\n17.851  runc             231218 1599     0 /usr/bin/runc --version\n17.859  runc             231233 1599     0 /usr/bin/runc --version\n17.859  docker-init      231232 1599     0 /usr/bin/docker-init --version\n17.863  docker-init      231241 1599     0 /usr/bin/docker-init --version\n17.864  runc             231242 1599     0 /usr/bin/runc --version\n17.869  docker-init      231249 1599     0 /usr/bin/docker-init --version\n17.870  docker           231250 230593   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.875  runc             231257 1599     0 /usr/bin/runc --version\n17.879  docker           231263 230716   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.881  docker-init      231264 1599     0 /usr/bin/docker-init --version\n17.885  docker-init      231272 1599     0 /usr/bin/docker-init --version\n17.893  docker           231273 230770   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.897  runc             231283 1599     0 /usr/bin/runc --version\n17.901  docker           231289 230815   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.907  docker-init      231296 1599     0 /usr/bin/docker-init --version\n17.910  runc             231297 1599     0 /usr/bin/runc --version\n17.914  runc             231304 1599     0 /usr/bin/runc --version\n17.941  powerpc64le-lin  231312 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n17.943  powerpc64le-lin  231313 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n17.947  cc1plus          231314 231313   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n17.959  cc1plus          231315 231312   0 \n17.963  rustup           231316 230593   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.963  rustup           231317 230681   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.964  docker-init      231318 1599     0 /usr/bin/docker-init --version\n17.972  rustup           231337 230593   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.972  runc             231335 1599     0 \n17.972  rustup           231338 230681   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.996  systemd-sysctl   231364 231355   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethdd37870 --prefix=/net/ipv4/neigh/vethdd37870 --prefix=/net/ipv6/conf/vethdd37870 --prefix=/net/ipv6/neigh/vethdd37870\n17.996  systemd-sysctl   231358 231356   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethee811d7 --prefix=/net/ipv4/neigh/vethee811d7 --prefix=/net/ipv6/conf/vethee811d7 --prefix=/net/ipv6/neigh/vethee811d7\n18.001  docker-init      231336 1599     0 /usr/bin/docker-init --version\n18.001  rustup           231365 230716   0 /home/xmoe/.cargo/bin/rustup toolchain list\n18.002  docker-init      231366 1599     0 /usr/bin/docker-init --version\n18.014  rustup           231380 230716   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n18.017  rustup           231377 230681   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.047  containerd-shim  231423 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e721041d49 start\n18.049  uname            231427 230681   0 /usr/bin/uname -r\n18.049  rustup           231428 230815   0 /home/xmoe/.cargo/bin/rustup toolchain list\n18.052  containerd-shim  231433 231423   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e721041d49 -address /var/run/docker/containerd/containerd.sock\n18.057  runc             231451 231433   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e7210 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e7210 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e7210 9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e721041d49\n18.059  rustup           231455 230815   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n18.062  powerpc64le-lin  231459 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n18.065  cc1plus          231469 231459   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n18.067  rustup           231470 230716   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.070  exe              231471 231451   0 /proc/self/exe init\n18.097  rustup           231482 230815   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.107  uname            231492 230716   0 /usr/bin/uname -r\n18.116  docker           231493 230681   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n18.133  rustup           231502 230770   0 /home/xmoe/.cargo/bin/rustup toolchain list\n18.138  docker           231516 230716   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n18.143  rustup           231522 230770   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n18.174  exe              231531 231451   0 /proc/1599/exe -exec-root=/var/run/docker 9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e721041d49 d7da31e8f8e1\n18.192  rustup           231543 230770   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.213  systemd-sysctl   231555 231401   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth9934856 --prefix=/net/ipv4/neigh/veth9934856 --prefix=/net/ipv6/conf/veth9934856 --prefix=/net/ipv6/neigh/veth9934856\n18.217  systemd-sysctl   231556 231414   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe119a28 --prefix=/net/ipv4/neigh/vethe119a28 --prefix=/net/ipv6/conf/vethe119a28 --prefix=/net/ipv6/neigh/vethe119a28\n18.226  exe              231557 1599     0 /proc/self/exe /var/run/docker/netns/3891ca36ee5d all false\n18.247  containerd-shim  231568 1663     0 \n18.252  containerd-shim  231574 231568   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 50baf8ba78f50747c45965feaea935725c9479f26e775a94aa494e77e8b912b8 -address /var/run/docker/containerd/containerd.sock\n18.264  runc             231587 231574   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/50baf8ba78f50747c45965feaea935725c9479f26e775a94aa494e77e8b --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/50baf8ba78f50747c45965feaea935725c9479f26e775a94aa494e77e8b --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/50baf8ba78f50747c45965feaea935725c9479f26e775a94aa494e77e8b 50baf8ba78f50747c45965feaea935725c9479f26e775a94aa494e77e8b912b8\n18.279  exe              231595 231587   0 /proc/self/exe init\n18.323  rustup           231597 230593   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.331  uname            231606 230770   0 /usr/bin/uname -r\n18.331  uname            231607 230815   0 /usr/bin/uname -r\n18.374  docker           231608 230770   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n18.387  systemd-sysctl   231620 231567   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb266392 --prefix=/net/ipv4/neigh/vethb266392 --prefix=/net/ipv6/conf/vethb266392 --prefix=/net/ipv6/neigh/vethb266392\n18.390  systemd-sysctl   231615 231405   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethda7c6d7 --prefix=/net/ipv4/neigh/vethda7c6d7 --prefix=/net/ipv6/conf/vethda7c6d7 --prefix=/net/ipv6/neigh/vethda7c6d7\n18.414  uname            231626 230593   0 /usr/bin/uname -r\n18.425  containerd-shim  231627 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c036fbb start\n18.435  containerd-shim  231634 231627   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c036fbb -address /var/run/docker/containerd/containerd.sock\n18.439  runc             231644 231433   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e7210 --log-format json --systemd-cgroup start 9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e721041d49\n18.439  runc             231645 231634   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c0 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c0 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c0 c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c036fbb\n18.447  docker           231656 230815   0 \n18.447  docker           231657 230593   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n18.449  sh               231483 231433   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n18.454  cargo            231668 231483   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n18.456  exe              231681 231645   0 /proc/self/exe init\n18.469  rustc            231682 230948   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.477  rustc            231683 230543   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n18.488  exe              231694 231587   0 /proc/1599/exe -exec-root=/var/run/docker 50baf8ba78f50747c45965feaea935725c9479f26e775a94aa494e77e8b912b8 d7da31e8f8e1\n18.496  cargo-native-tr  231668 231483   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n18.497  systemd-sysctl   231703 231401   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf838d78 --prefix=/net/ipv4/neigh/vethf838d78 --prefix=/net/ipv6/conf/vethf838d78 --prefix=/net/ipv6/neigh/vethf838d78\n18.497  systemd-sysctl   231702 231414   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth27f8c07 --prefix=/net/ipv4/neigh/veth27f8c07 --prefix=/net/ipv6/conf/veth27f8c07 --prefix=/net/ipv6/neigh/veth27f8c07\n18.497  rustc            231683 230543   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n18.531  cargo            231708 231668   0 \n18.538  exe              231737 1599     0 /proc/self/exe /var/run/docker/netns/5a373f7d76a3 all false\n18.538  rustc            231725 231708   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.538  docker           231726 230543   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n18.538  docker           231714 230543   0 /usr/bin/docker --help\n18.538  containerd-shim  231728 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 005a30947f53fcdc8ab0c974bf80257173816e3f63a4d05fe559ab13628a213f start\n18.538  rustc            231724 230949   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.540  containerd-shim  231742 231728   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 005a30947f53fcdc8ab0c974bf80257173816e3f63a4d05fe559ab13628a213f -address /var/run/docker/containerd/containerd.sock\n18.554  runc             231759 1599     0 /usr/bin/runc --version\n18.560  docker-init      231767 1599     0 /usr/bin/docker-init --version\n18.569  docker           231769 230543   0 /usr/bin/docker info -f {{.SecurityOptions}}\n18.576  runc             231776 231742   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/005a30947f53fcdc8ab0c974bf80257173816e3f63a4d05fe559ab13628 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/005a30947f53fcdc8ab0c974bf80257173816e3f63a4d05fe559ab13628 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/005a30947f53fcdc8ab0c974bf80257173816e3f63a4d05fe559ab13628 005a30947f53fcdc8ab0c974bf80257173816e3f63a4d05fe559ab13628a213f\n18.583  exe              231786 231776   0 /proc/self/exe init\n18.585  exe              231788 231645   0 /proc/1599/exe   \n18.588  rustc            231789 231708   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n18.594  runc             231797 1599     0 /usr/bin/runc --version\n18.598  systemd-sysctl   231803 231401   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth21e9547 --prefix=/net/ipv4/neigh/veth21e9547 --prefix=/net/ipv6/conf/veth21e9547 --prefix=/net/ipv6/neigh/veth21e9547\n18.601  docker-init      231807 1599     0 /usr/bin/docker-init --version\n18.626  rustc            231810 230875   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n18.645  rustc            231819 230871   0 \n18.645  rustc            231810 230875   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n18.645  rustup           231829 230543   0 \n18.645  exe              231831 1599     0 /proc/self/exe /var/run/docker/netns/ff1f3950e33e all false\n18.646  rustc            231819 230871   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n18.652  docker           231847 230875   0 /usr/bin/docker --help\n18.653  rustup           231848 230543   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n18.655  systemd-sysctl   231849 231414   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc710035 --prefix=/net/ipv4/neigh/vethc710035 --prefix=/net/ipv6/conf/vethc710035 --prefix=/net/ipv6/neigh/vethc710035\n18.656  systemd-sysctl   231854 231420   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethed0b790 --prefix=/net/ipv4/neigh/vethed0b790 --prefix=/net/ipv6/conf/vethed0b790 --prefix=/net/ipv6/neigh/vethed0b790\n18.657  systemd-sysctl   231857 231406   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethedc8fc4 --prefix=/net/ipv4/neigh/vethedc8fc4 --prefix=/net/ipv6/conf/vethedc8fc4 --prefix=/net/ipv6/neigh/vethedc8fc4\n18.692  execsnoop        231881 231668   0 /usr/local/bin/execsnoop -t\n18.692  containerd-shim  231895 231855   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c60f58a -address /var/run/docker/containerd/containerd.sock\n18.692  docker           231906 230875   0 \n18.692  runc             231910 231895   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c6 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c6 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c6 84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c60f58a\n18.692  docker           231917 230871   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n18.692  containerd-shim  231855 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c60f58a start\n18.692  docker           231880 230871   0 \n18.692  python3          231881 231668   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n18.696  runc             231928 231574   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/50baf8ba78f50747c45965feaea935725c9479f26e775a94aa494e77e8b --log-format json --systemd-cgroup start 50baf8ba78f50747c45965feaea935725c9479f26e775a94aa494e77e8b912b8\n18.696  rustup           231927 230543   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.698  exe              231936 231910   0 /proc/self/exe init\n18.705  sh               231614 231574   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n18.707  cargo            231948 231614   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n18.717  runc             231949 1599     0 /usr/bin/runc --version\n18.717  exe              231950 231776   0 /proc/1599/exe -exec-root=/var/run/docker 005a30947f53fcdc8ab0c974bf80257173816e3f63a4d05fe559ab13628a213f d7da31e8f8e1\n18.726  docker-init      231962 1599     0 /usr/bin/docker-init --version\n18.728  cargo-native-tr  231948 231614   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n18.730  docker           231963 230871   0 /usr/bin/docker info -f {{.SecurityOptions}}\n18.736  runc             231970 1599     0 /usr/bin/runc --version\n18.736  cargo            231965 231948   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n18.737  uname            231972 230543   0 /usr/bin/uname -r\n18.754  runc             231977 1599     0 /usr/bin/runc --version\n18.754  rustc            231978 231965   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.790  docker           231995 230875   0 \n18.790  exe              231989 1599     0 /proc/self/exe /var/run/docker/netns/2d4bafcda6bd all false\n18.790  docker-init      231990 1599     0 /usr/bin/docker-init --version\n18.792  docker           232007 230543   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n18.797  cargo            232015 230411   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n18.799  docker-init      232019 1599     0 /usr/bin/docker-init --version\n18.800  rustc            232018 231965   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n18.832  rustc            232023 232015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.854  runc             232028 1599     0 /usr/bin/runc --version\n18.859  containerd-shim  232034 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a2d3a3cebe327f99386114c35bd96bc6147822d9863d0bc9494f42fe893a0b85 start\n18.860  docker-init      232035 1599     0 /usr/bin/docker-init --version\n18.871  containerd-shim  232047 232034   0 \n18.878  rustup           232056 230871   0 /home/xmoe/.cargo/bin/rustup toolchain list\n18.884  runc             232057 232047   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a2d3a3cebe327f99386114c35bd96bc6147822d9863d0bc9494f42fe893 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a2d3a3cebe327f99386114c35bd96bc6147822d9863d0bc9494f42fe893 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a2d3a3cebe327f99386114c35bd96bc6147822d9863d0bc9494f42fe893 a2d3a3cebe327f99386114c35bd96bc6147822d9863d0bc9494f42fe893a0b85\n18.896  rustup           232073 230871   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n18.897  rustup           232074 230875   0 /home/xmoe/.cargo/bin/rustup toolchain list\n18.910  exe              232072 232057   0 \n18.911  rustup           232091 230875   0 \n18.939  execsnoop        232102 231948   0 /usr/local/bin/execsnoop -t\n18.941  python3          232102 231948   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n18.949  rustc            232103 232015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_width --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"cjk\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n18.955  rustup           232110 230875   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.977  rustc            232119 232015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name memchr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n18.978  rustc            232120 232015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pulldown_cmark_escape --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pulldown-cmark-escape-0.11.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"simd\")) -C metadata=4bd53abb8701dcef ...\n18.978  rustc            232125 232015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bitflags --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.8.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\", \"bytemuck\", \"compiler_builtins\", \"core\", \"example_generated\", \"rustc-dep-of-std\", \"serde\", \"std -C metadata=2c953780ec993778 ...\n18.978  rustc            232117 232015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicase --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicase-2.8.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"nightly\")) -C metadata=029785130794bfe3 ...\n18.979  rustc            232130 232015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --cfg feature=\"default\" --cfg feature=\"getopts\" --cfg ...\n18.997  runc             232148 231742   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/005a30947f53fcdc8ab0c974bf80257173816e3f63a4d05fe559ab13628 --log-format json --systemd-cgroup start 005a30947f53fcdc8ab0c974bf80257173816e3f63a4d05fe559ab13628a213f\n19.003  exe              232155 231910   0 /proc/1599/exe -exec-root=/var/run/docker 84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c60f58a d7da31e8f8e1\n19.009  sh               231834 231742   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n19.011  cargo            232163 231834   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n19.023  systemd-sysctl   232168 231414   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethffd302e --prefix=/net/ipv4/neigh/vethffd302e --prefix=/net/ipv6/conf/vethffd302e --prefix=/net/ipv6/neigh/vethffd302e\n19.023  uname            232169 230875   0 /usr/bin/uname -r\n19.024  systemd-sysctl   232167 231401   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf4dab3c --prefix=/net/ipv4/neigh/vethf4dab3c --prefix=/net/ipv6/conf/vethf4dab3c --prefix=/net/ipv6/neigh/vethf4dab3c\n19.041  cargo-native-tr  232163 231834   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n19.043  rustup           232179 230871   0 \n19.047  exe              232181 232057   0 /proc/1599/exe -exec-root=/var/run/docker a2d3a3cebe327f99386114c35bd96bc6147822d9863d0bc9494f42fe893a0b85 d7da31e8f8e1\n19.047  cargo            232180 232163   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n19.059  cargo            232187 230445   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n19.067  exe              232197 1599     0 /proc/self/exe /var/run/docker/netns/963e751319cc all false\n19.070  docker           232198 230875   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n19.079  rustc            232210 232180   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.090  rustc            232215 232187   0 \n19.094  exe              232221 1599     0 \n19.096  rustc            232223 232180   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n19.117  uname            232245 230871   0 /usr/bin/uname -r\n19.133  containerd-shim  232249 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a13797654060bc617eadbdf2de9a0ddd5064c7336e66cdae32473a70c9a6f758 start\n19.138  containerd-shim  232256 232249   0 \n19.145  cc               232258 232130   0 /tmp/native-trace-230411-1783993336672/shims/cc -m64 /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n19.145  execsnoop        232269 232163   0 /usr/local/bin/execsnoop -t\n19.145  runc             232270 232256   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a13797654060bc617eadbdf2de9a0ddd5064c7336e66cdae32473a70c9a --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a13797654060bc617eadbdf2de9a0ddd5064c7336e66cdae32473a70c9a --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a13797654060bc617eadbdf2de9a0ddd5064c7336e66cdae32473a70c9a a13797654060bc617eadbdf2de9a0ddd5064c7336e66cdae32473a70c9a6f758\n19.146  python3          232269 232163   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n19.146  docker           232272 230871   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n19.148  cc               232278 232258   0 /usr/bin/cc -m64 /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n19.150  rustc            232282 232187   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bitflags --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.8.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\", \"bytemuck\", \"compiler_builtins\", \"core\", \"example_generated\", \"rustc-dep-of-std\", \"serde\", \"std -C metadata=36881999aa281e81 ...\n19.155  rustc            232292 232187   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_width --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"cjk\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n19.158  rustc            232274 232187   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --cfg feature=\"default\" --cfg feature=\"getopts\" --cfg ...\n19.163  rustc            232301 232187   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicase --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicase-2.8.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"nightly\")) -C metadata=2c88d6915fd715d2 ...\n19.163  rustc            232294 232187   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name memchr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n19.164  rustc            232296 232187   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pulldown_cmark_escape --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pulldown-cmark-escape-0.11.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"simd\")) -C metadata=3860ee446f168590 ...\n19.165  collect2         232293 232278   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfeM0YZ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.167  ld.lld           232304 232293   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfeM0YZ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a ...\n19.173  rust-lld         232304 232293   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfeM0YZ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.178  runc             232248 231634   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c0 --log-format json --systemd-cgroup start c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c036fbb\n19.194  sh               231699 231634   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n19.200  cargo            232333 231699   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n19.209  runc             232338 231895   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c6 --log-format json --systemd-cgroup start 84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c60f58a\n19.219  sh               232106 231895   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n19.219  exe              232303 232270   0 /proc/self/exe init\n19.225  cargo            232350 232106   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n19.242  cargo-native-tr  232333 231699   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n19.251  cargo            232356 232333   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n19.257  cargo-native-tr  232350 232106   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n19.267  cargo            232362 232350   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n19.313  rustc            232366 232356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.313  build-script-bu  232365 232015   0 \n19.314  systemd-sysctl   232381 231401   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth519ed85 --prefix=/net/ipv4/neigh/veth519ed85 --prefix=/net/ipv6/conf/veth519ed85 --prefix=/net/ipv6/neigh/veth519ed85\n19.314  systemd-sysctl   232379 231414   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethafd3855 --prefix=/net/ipv4/neigh/vethafd3855 --prefix=/net/ipv6/conf/vethafd3855 --prefix=/net/ipv6/neigh/vethafd3855\n19.397  rustc            232392 232356   0 \n19.397  rustc            232390 232362   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.397  cargo            232395 232133   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n19.397  cargo-native-tr  232395 232133   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n19.397  containerd-shim  232405 1663     0 \n19.397  execsnoop        232409 232333   0 /usr/local/bin/execsnoop -t\n19.397  python3          232409 232333   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n19.397  containerd-shim  232416 232405   0 \n19.397  runc             232441 232416   0 \n19.397  sh               232133 232047   0 \n19.397  systemd-sysctl   232399 231356   0 \n19.397  runc             232384 232047   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a2d3a3cebe327f99386114c35bd96bc6147822d9863d0bc9494f42fe893 --log-format json --systemd-cgroup start a2d3a3cebe327f99386114c35bd96bc6147822d9863d0bc9494f42fe893a0b85\n19.399  cargo            232417 232395   0 \n19.399  execsnoop        232418 232350   0 \n19.399  python3          232418 232350   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n19.399  as               232419 229482   0 \n19.399  containerd-shim  232429 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 8f7a7bd94d562343c07279149835aba7e953de145eeeddef49adf64892df7984 start\n19.399  containerd-shim  232442 232429   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 8f7a7bd94d562343c07279149835aba7e953de145eeeddef49adf64892df7984 -address /var/run/docker/containerd/containerd.sock\n19.399  runc             232459 232442   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8f7a7bd94d562343c07279149835aba7e953de145eeeddef49adf64892d --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8f7a7bd94d562343c07279149835aba7e953de145eeeddef49adf64892d --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8f7a7bd94d562343c07279149835aba7e953de145eeeddef49adf64892d 8f7a7bd94d562343c07279149835aba7e953de145eeeddef49adf64892df7984\n19.399  rustc            232396 232362   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n19.399  systemd-sysctl   232398 231420   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd9e0e2a --prefix=/net/ipv4/neigh/vethd9e0e2a --prefix=/net/ipv6/conf/vethd9e0e2a --prefix=/net/ipv6/neigh/vethd9e0e2a\n19.401  exe              232464 232441   0 /proc/self/exe init\n19.405  exe              232470 232459   0 /proc/self/exe init\n19.408  rustc            232468 232187   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name getopts --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getopts-0.2.21/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"core\", \"rustc-dep-of-std\", \"std\")) -C metadata=3ae2bfa83c9fd852 ...\n19.415  rustc            232473 232417   0 /usr/bin/rustc -vV\n19.431  rustc            232476 232417   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n19.471  execsnoop        232480 232395   0 /usr/local/bin/execsnoop -t\n19.471  python3          232480 232395   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n19.502  exe              232496 232270   0 /proc/1599/exe -exec-root=/var/run/docker a13797654060bc617eadbdf2de9a0ddd5064c7336e66cdae32473a70c9a6f758 d7da31e8f8e1\n19.507  rustc            232498 232015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name getopts --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getopts-0.2.21/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"core\", \"rustc-dep-of-std\", \"std\")) -C metadata=cc848890360245b1 ...\n19.508  cc               232467 232274   0 /tmp/native-trace-230445-1783993336797/shims/cc -m64 /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcdpHTIq/symbols.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.0pjbxil.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.0pjbxil.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.0pjbxil.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.0pjbxil.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.0pjbxil.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.0pjbxil.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n19.535  cc               232511 232467   0 /usr/bin/cc -m64 /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcdpHTIq/symbols.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.0pjbxil.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.0pjbxil.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.0pjbxil.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.0pjbxil.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.0pjbxil.rcgu.o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.0pjbxil.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n19.546  collect2         232514 232511   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cconuQpV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.548  exe              232516 1599     0 /proc/self/exe /var/run/docker/netns/f2da248364f8 all false\n19.555  ld.lld           232517 232514   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cconuQpV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a ...\n19.558  rust-lld         232517 232514   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cconuQpV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.564  exe              232527 232441   0 \n19.566  exe              232528 232459   0 /proc/1599/exe -exec-root=/var/run/docker 8f7a7bd94d562343c07279149835aba7e953de145eeeddef49adf64892df7984 d7da31e8f8e1\n19.607  exe              232564 1599     0 /proc/self/exe /var/run/docker/netns/059c170244a1 all false\n19.610  exe              232565 1599     0 /proc/self/exe /var/run/docker/netns/c54fb9590b1c all false\n19.675  runc             232585 232256   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a13797654060bc617eadbdf2de9a0ddd5064c7336e66cdae32473a70c9a --log-format json --systemd-cgroup start a13797654060bc617eadbdf2de9a0ddd5064c7336e66cdae32473a70c9a6f758\n19.685  sh               232358 232256   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n19.687  cargo            232591 232358   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n19.709  runc             232592 232416   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aec7b5f96dc6125e3c9d623e698cbb9a005a2a228f21fa301b39dfe20fb --log-format json --systemd-cgroup start aec7b5f96dc6125e3c9d623e698cbb9a005a2a228f21fa301b39dfe20fbb451e\n19.719  cargo-native-tr  232591 232358   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n19.723  sh               232486 232416   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n19.731  cargo            232603 232591   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n19.732  cargo            232600 232486   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n19.732  build-script-bu  232605 232187   0 /target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build-script-build\n19.752  cargo-native-tr  232600 232486   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n19.760  as               232607 230504   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/644b6a24ae2ff5c1-blob_file_garbage.o /tmp/ccYD0lOQ.s\n19.765  cargo            232609 232600   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n19.769  rustc            232613 232015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pulldown_cmark --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --cfg feature=\"default\" --cfg feature=\"getopts\" --cfg ...\n19.791  rustc            232614 232603   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.818  rustc            232621 232603   0 \n19.823  rustc            232623 232609   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.873  rustc            232629 232609   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n19.913  as               232633 229542   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/40a8ecc0aa07be2f-secondary_cache.o /tmp/ccPCEfwl.s\n19.922  execsnoop        232639 232591   0 /usr/local/bin/execsnoop -t\n19.922  python3          232639 232591   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n19.939  runc             232619 232442   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8f7a7bd94d562343c07279149835aba7e953de145eeeddef49adf64892d --log-format json --systemd-cgroup start 8f7a7bd94d562343c07279149835aba7e953de145eeeddef49adf64892df7984\n19.953  sh               232497 232442   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n19.953  cargo            232648 232497   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n19.972  execsnoop        232649 232600   0 /usr/local/bin/execsnoop -t\n19.972  python3          232649 232600   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n19.996  cargo-native-tr  232648 232497   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n20.007  cargo            232652 232648   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n20.064  rustc            232653 232652   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.101  rustc            232656 232652   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.217  powerpc64le-lin  232661 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n20.229  cc1plus          232663 232661   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n20.233  execsnoop        232660 232648   0 /usr/local/bin/execsnoop -t\n20.235  python3          232660 232648   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n20.261  powerpc64le-lin  232662 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n20.270  cc1plus          232666 232662   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n20.502  riscv64-linux-g  232671 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n20.508  cc1plus          232673 232671   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n20.608  rustc            232679 232187   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pulldown_cmark --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --cfg feature=\"default\" --cfg feature=\"getopts\" --cfg ...\n20.913  sh               232684 2147557   0 /bin/sh -c which ps\n20.914  which            232684 2147557   0 /usr/bin/which ps\n20.918  sh               232685 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n20.920  ps               232685 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n20.982  sh               232686 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n20.984  cpuUsage.sh      232686 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n20.987  sed              232687 232686   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n20.990  cat              232688 232686   0 /usr/bin/cat /proc/2240539/stat\n20.994  cat              232689 232686   0 /usr/bin/cat /proc/4193716/stat\n20.997  sleep            232690 232686   0 /usr/bin/sleep 1\n"
    },
    {
      "argv": [
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 228177,
      "build_script_target_dir": "pulldown-cmark-3bfaa0284ef6cd6a",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build-script-build",
      "pid": 228177,
      "ppid": 228064,
      "root_cargo_pid": 228064,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "pulldown-cmark",
      "cwd": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
      "event_id": "bsrun:dcc79535ed866cb1:7a6292397c2722f9:45329bbb65dbee50",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
      "out_dir": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
      "success": true,
      "target": null,
      "version": "0.13.0",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-aarch64-e8qxx5kl/src/pulldown-cmark-0.13.0",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
  "item": {
    "rank": 1090,
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "crate_id": "2303",
    "version_id": "1444037",
    "downloads": 18304340,
    "cumulative_downloads": 91223320538,
    "cumulative_share_of_global": 0.3410629360575566,
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
