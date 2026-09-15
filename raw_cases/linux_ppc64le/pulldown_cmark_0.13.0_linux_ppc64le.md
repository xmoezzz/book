# `pulldown-cmark` `0.13.0`

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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj",
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
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-232258-1783993341497649568.map",
  "pid": 232258,
  "ppid": 232130,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-232258-1783993341497649568.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
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
  "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "workspace_root": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0"
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
      "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
      "name": "pulldown-cmark",
      "version": "0.13.0",
      "manifest_path": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0"
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 232258,
  "ppid": 232130,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "event_id": "used:cc:7f614eb0daeae15c:1661cb0a62de273a:154f8437eefadc83",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
  "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
  "pid": 232258,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "event_id": "used:cc:7f614eb0daeae15c:2a53e4393c7c814d:154f8437eefadc83",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
  "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
  "pid": 232258,
  "sha256": "d31c7e1d4b8ab3e8ed82153f77c66a05ecdd7dd7b213a31010d55de15857e91d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "event_id": "used:cc:7f614eb0daeae15c:7b83443f27ad00cd:154f8437eefadc83",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
  "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
  "pid": 232258,
  "sha256": "5fd587170252d77b20ffe09f58156b43afb28881c27e505ea7ca9aa0d4b7e6e2",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "event_id": "used:cc:7f614eb0daeae15c:a02501081a43c9d4:154f8437eefadc83",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
  "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
  "pid": 232258,
  "sha256": "bc54e3e2281719a8cd9fa152724bdaa0b2f6a4bcf34048625b2c97535796b6ff",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "event_id": "used:cc:7f614eb0daeae15c:a64f60427e586378:154f8437eefadc83",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
  "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
  "pid": 232258,
  "sha256": "3f48625142798e15e093ede66eefbfc14a18ba73a6c55326a8c9ecaba3990277",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "event_id": "used:cc:7f614eb0daeae15c:fa0a4721983e273f:154f8437eefadc83",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
  "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
  "pid": 232258,
  "sha256": "bbb6c5eae70af173367a9cc072f67f4805e488e5260c15f04427db52ff957f78",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "event_id": "used:cc:7f614eb0daeae15c:312519c4a59779fc:154f8437eefadc83",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
  "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
  "pid": 232258,
  "sha256": "a4914eb4d43ad45db892635f72dd262e44cb35a20e5a76b2a5ff53c9a3de75b6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "cargo_pkg_name": "pulldown-cmark",
  "cargo_pkg_version": "0.13.0",
  "context_path": "/tmp/native-trace-230411-1783993336672/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-230411-1783993336672/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 232258,
  "ppid": 232130,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
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
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj",
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
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
      "kind": "object",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-232258-1783993341497649568.map",
  "pid": 232258,
  "ppid": 232130,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-232258-1783993341497649568.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
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
  "parsed_event_count": 1056,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1057,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "dex.crates.io-1949cf8c6b5b557f/getrandom-0.2.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"custom\", \"js\", \"js-sys\", \"rdrand\", \"rustc-dep-of-std\", \"std\", \"test-in-browser ...\n16.466  build-script-bu  236681 236108   0 /target/debug/build/serde-cc51c28a4bad2951/build-script-build\n16.475  rustc            236683 236681   0 \n16.603  rustc            236695 236108   0 \n16.619  rustc            236696 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand_core --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"getrandom\" --cfg feature=\"std\" ...\n16.659  rustc            236701 233032   0 \n16.673  rustc            236708 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot-0.12.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arc_lock\", \"deadlock_detection\", \"default\", \"hardware-lock-elision\", \"nightly\", \"owning_ref\", \"send_guard\", ...\n16.702  rustc            236718 233032   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand_chacha --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"serde\", \"serde1\", \"simd\", \"std\")) ...\n16.735  as               236731 229553   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/644b6a24ae2ff5c1-blob_fetcher.o /tmp/cckbePrT.s\n16.739  powerpc64le-lin  236723 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n16.748  cc1plus          236733 236723   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n16.808  runc             236737 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2639903245 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n16.820  riscv64-linux-g  236744 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n16.823  exe              236746 236737   0 /proc/self/exe init\n16.846  cc1plus          236747 236744   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n16.874  curl             236751 236737   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n16.916  rustc            236764 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.17/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n16.942  rustc            236768 233032   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"getrandom\" ...\n16.964  rustc            236738 234231   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name string_cache --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/string_cache-0.8.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"serde\" --cfg feature=\"serde_support\" ...\n16.971  rustc            236781 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand_chacha --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"serde\", \"serde1\", \"simd\", \"std\")) ...\n17.179  rustc            236801 233581   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ppv_lite86 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.21/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"simd\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n17.265  sh               236814 2147557   0 /bin/sh -c which ps\n17.267  which            236814 2147557   0 /usr/bin/which ps\n17.271  sh               236817 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.273  ps               236817 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.282  rustc            236816 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"getrandom\" ...\n17.337  sh               236823 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n17.337  cpuUsage.sh      236823 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n17.342  sed              236825 236823   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.346  cat              236827 236823   0 \n17.346  cat              236826 236823   0 /usr/bin/cat /proc/2240539/stat\n17.347  sleep            236828 236823   0 /usr/bin/sleep 1\n17.426  as               236834 229094   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/644b6a24ae2ff5c1-blob_fetcher.o /tmp/ccbIqYrb.s\n17.444  rustc            236833 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.17/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n17.539  rustc            236842 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot_core --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot_core-0.9.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"backtrace\", \"deadlock_detection\", \"nightly\", \"petgraph\", \"thread-id\")) -C metadata=ba2ec95b61885fb8 ...\n17.696  rustc            236851 233581   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand_chacha --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"serde\", \"serde1\", \"simd\", \"std\")) ...\n17.715  rustc            236856 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-1.0.89/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n17.823  rustc            236869 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-1.0.89/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n17.925  rustc            236877 233581   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"getrandom\" ...\n17.973  rustc            236887 234231   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ppv_lite86 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.21/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"simd\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n17.976  rustc            236893 233032   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_generator --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.10.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"criterion\")) -C metadata=33cbcd4cf8bd70f8 ...\n17.986  rustc            236895 233032   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_generator --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.11.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"criterion\")) -C metadata=9b0d7500eeb5b8d5 ...\n17.990  rustc            236901 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name getrandom --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"custom\", \"js\", \"js-sys\", \"rdrand\", \"rustc-dep-of-std\", \"std\", \"test-in-browser ...\n18.071  rustc            236917 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot-0.12.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arc_lock\", \"deadlock_detection\", \"default\", \"hardware-lock-elision\", \"nightly\", \"owning_ref\", \"send_guard\", ...\n18.107  rustc            236920 233032   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_codegen --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.10.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=83b98398b575e289 ...\n18.134  rustc            236931 233032   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name string_cache_codegen --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/string_cache_codegen-0.5.4/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=1dea28fdcb7dc932 ...\n18.161  rustc            236938 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand_core --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"getrandom\" --cfg feature=\"std\" ...\n18.346  rustc            236954 234231   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand_chacha --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"serde\", \"serde1\", \"simd\", \"std\")) ...\n18.350  sed              236956 236823   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.354  cat              236957 236823   0 /usr/bin/cat /proc/2240539/stat\n18.356  cat              236959 236823   0 /usr/bin/cat /proc/4193716/stat\n18.405  riscv64-linux-g  236964 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n18.407  as               236965 229519   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/40a8ecc0aa07be2f-cache.o /tmp/ccT8xf0j.s\n18.443  cc1plus          236966 236964   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n18.542  rustc            236975 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_generator --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.10.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"criterion\")) -C metadata=905fcc6afc71b676 ...\n18.565  rustc            236984 234231   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"getrandom\" ...\n18.612  rustc            236998 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_codegen --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.10.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=93b54f05441d9d5f ...\n18.621  rustc            237000 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand_chacha --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"serde\", \"serde1\", \"simd\", \"std\")) ...\n18.635  rustc            237001 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name string_cache_codegen --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/string_cache_codegen-0.5.2/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=947e25622fb6be5b ...\n18.806  rustc            237026 233581   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_generator --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.10.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"criterion\")) -C metadata=33cbcd4cf8bd70f8 ...\n18.811  rustc            237027 233581   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_generator --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.11.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"criterion\")) -C metadata=9b0d7500eeb5b8d5 ...\n18.837  rustc            237018 233032   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=d1b9fd6f7f6cda03 ...\n18.950  aarch64-linux-g  237042 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n18.961  cc1plus          237043 237042   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n18.994  rustc            237048 233581   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_codegen --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.10.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=83b98398b575e289 ...\n19.035  rustc            237056 233581   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name string_cache_codegen --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/string_cache_codegen-0.5.4/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=1dea28fdcb7dc932 ...\n19.224  rustc            237085 236108   0 \n19.387  rustc            237151 234231   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_generator --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.11.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"criterion\")) -C metadata=9b0d7500eeb5b8d5 ...\n19.454  rustc            237152 234231   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_generator --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.10.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"criterion\")) -C metadata=33cbcd4cf8bd70f8 ...\n19.496  cc               237213 237018   0 /tmp/native-trace-231948-1783993341078/shims/cc -m64 /target/debug/build/markup5ever-31838724984befce/rustcvc0mDI/symbols.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.00bugusk6670k49tcjhp371ib.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09or6hn0xtain3gkyopvciaz0.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09sxli55pm82xazi37z60169v.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0b7u0z26r89so21w6r1dksf6o.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0dvoqnvzwqw4gef85cqrcwblr.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0nrlwiynckpwo0gnfqgxlb5i5.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0qtoiy8zcntvir7a8lkyni6mr.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0rzuw3jj5qxboflpyrn14r4oy.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xmg0bm2ibunyeuzoj1b3b6rk.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xonkzg6bej7y03ibebgtt9b8.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1951ev2fh8qfq6v6atu5b5u0f.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1fq8ad0hcdujygb3gv350fju8.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1k15psoggxaxsgztj11cr3yxs.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1kbjez9nz1obex56s414wti6f.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.24hferydrrp2dmi07dhvubo6e.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2514ggscyvvp3o7z2icusuw1w.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2afw7f114lj0w3pa6qpqmoz5o.1qkk8go.rcgu.o ...\n19.503  cc               237214 237213   0 /usr/bin/cc -m64 /target/debug/build/markup5ever-31838724984befce/rustcvc0mDI/symbols.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.00bugusk6670k49tcjhp371ib.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09or6hn0xtain3gkyopvciaz0.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09sxli55pm82xazi37z60169v.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0b7u0z26r89so21w6r1dksf6o.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0dvoqnvzwqw4gef85cqrcwblr.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0nrlwiynckpwo0gnfqgxlb5i5.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0qtoiy8zcntvir7a8lkyni6mr.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0rzuw3jj5qxboflpyrn14r4oy.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xmg0bm2ibunyeuzoj1b3b6rk.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xonkzg6bej7y03ibebgtt9b8.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1951ev2fh8qfq6v6atu5b5u0f.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1fq8ad0hcdujygb3gv350fju8.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1k15psoggxaxsgztj11cr3yxs.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1kbjez9nz1obex56s414wti6f.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.24hferydrrp2dmi07dhvubo6e.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2514ggscyvvp3o7z2icusuw1w.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2afw7f114lj0w3pa6qpqmoz5o.1qkk8go.rcgu.o ...\n19.511  collect2         237216 237214   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1Iil2b.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.518  ld.lld           237221 237216   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1Iil2b.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce ...\n19.524  rust-lld         237221 237216   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1Iil2b.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.531  rustc            237222 234231   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_codegen --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.10.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=83b98398b575e289 ...\n19.603  rustc            237248 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/markup5ever-0.11.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=8e0b00d2b5a1934f ...\n19.630  rustc            237253 233581   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=d1b9fd6f7f6cda03 ...\n19.704  rustc            237263 234231   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name string_cache_codegen --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/string_cache_codegen-0.5.4/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=1dea28fdcb7dc932 ...\n19.824  build-script-bu  237270 233032   0 /target/debug/build/markup5ever-31838724984befce/build-script-build\n19.978  riscv64-linux-g  237273 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n19.983  cc1plus          237274 237273   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n20.136  rustc            237307 233032   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name markup5ever --edition=2018 lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=25728beef10be373 ...\n20.223  rustc            237337 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_generator --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.10.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"criterion\")) -C metadata=905fcc6afc71b676 ...\n20.233  rustc            237349 234231   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=d1b9fd6f7f6cda03 ...\n20.239  cc               237353 237248   0 /tmp/native-trace-235020-1783993349143/shims/cc -m64 /target/debug/build/markup5ever-a32dafa7969dc1b1/rustcUcQ8pz/symbols.o /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.0.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.1.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.2.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.7685p3eeoamip0z4pjuo4z4pe.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libstring_cache_codegen-226bca7e0be408b8.rlib /target/debug/deps/libquote-caa5a6f783f770e4.rlib /target/debug/deps/libproc_macro2-bcc52298e70ee541.rlib /target/debug/deps/libunicode_xid-bc2f9a71a9eadac1.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libphf_codegen-482db3ae92eb371b.rlib /target/debug/deps/libphf_generator-440742b73fd02201.rlib /target/debug/deps/librand-63ec678486dbfb81.rlib /target/debug/deps/librand_chacha-9e936d218899b44d.rlib /target/debug/deps/libppv_lite86-0a6ffb3623ef1b3c.rlib ...\n20.241  cc               237363 237353   0 /usr/bin/cc -m64 /target/debug/build/markup5ever-a32dafa7969dc1b1/rustcUcQ8pz/symbols.o /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.0.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.1.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.2.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.7685p3eeoamip0z4pjuo4z4pe.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libstring_cache_codegen-226bca7e0be408b8.rlib /target/debug/deps/libquote-caa5a6f783f770e4.rlib /target/debug/deps/libproc_macro2-bcc52298e70ee541.rlib /target/debug/deps/libunicode_xid-bc2f9a71a9eadac1.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libphf_codegen-482db3ae92eb371b.rlib /target/debug/deps/libphf_generator-440742b73fd02201.rlib /target/debug/deps/librand-63ec678486dbfb81.rlib /target/debug/deps/librand_chacha-9e936d218899b44d.rlib /target/debug/deps/libppv_lite86-0a6ffb3623ef1b3c.rlib ...\n20.248  collect2         237367 237363   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWNi5xt.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n20.259  ld.lld           237376 237367   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWNi5xt.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1 ...\n20.262  rust-lld         237376 237367   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWNi5xt.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n20.372  cc               237420 237253   0 /tmp/native-trace-232600-1783993342102/shims/cc -m64 /target/debug/build/markup5ever-31838724984befce/rustcl6ISXW/symbols.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.00bugusk6670k49tcjhp371ib.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09or6hn0xtain3gkyopvciaz0.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09sxli55pm82xazi37z60169v.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0b7u0z26r89so21w6r1dksf6o.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0dvoqnvzwqw4gef85cqrcwblr.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0nrlwiynckpwo0gnfqgxlb5i5.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0qtoiy8zcntvir7a8lkyni6mr.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0rzuw3jj5qxboflpyrn14r4oy.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xmg0bm2ibunyeuzoj1b3b6rk.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xonkzg6bej7y03ibebgtt9b8.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1951ev2fh8qfq6v6atu5b5u0f.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1fq8ad0hcdujygb3gv350fju8.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1k15psoggxaxsgztj11cr3yxs.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1kbjez9nz1obex56s414wti6f.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.24hferydrrp2dmi07dhvubo6e.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2514ggscyvvp3o7z2icusuw1w.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2afw7f114lj0w3pa6qpqmoz5o.0v8v8hx.rcgu.o ...\n20.377  cc               237437 237420   0 /usr/bin/cc -m64 /target/debug/build/markup5ever-31838724984befce/rustcl6ISXW/symbols.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.00bugusk6670k49tcjhp371ib.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09or6hn0xtain3gkyopvciaz0.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09sxli55pm82xazi37z60169v.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0b7u0z26r89so21w6r1dksf6o.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0dvoqnvzwqw4gef85cqrcwblr.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0nrlwiynckpwo0gnfqgxlb5i5.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0qtoiy8zcntvir7a8lkyni6mr.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0rzuw3jj5qxboflpyrn14r4oy.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xmg0bm2ibunyeuzoj1b3b6rk.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xonkzg6bej7y03ibebgtt9b8.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1951ev2fh8qfq6v6atu5b5u0f.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1fq8ad0hcdujygb3gv350fju8.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1k15psoggxaxsgztj11cr3yxs.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1kbjez9nz1obex56s414wti6f.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.24hferydrrp2dmi07dhvubo6e.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2514ggscyvvp3o7z2icusuw1w.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2afw7f114lj0w3pa6qpqmoz5o.0v8v8hx.rcgu.o ...\n20.394  collect2         237438 237437   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cch4dzx2.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n20.399  ld.lld           237439 237438   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cch4dzx2.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce ...\n20.404  rust-lld         237439 237438   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cch4dzx2.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n20.495  rustc            237462 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name string_cache_codegen --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/string_cache_codegen-0.5.2/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=947e25622fb6be5b ...\n20.495  rustc            237461 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_codegen --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.10.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=93b54f05441d9d5f ...\n20.575  build-script-bu  237476 235832   0 /target/debug/build/markup5ever-a32dafa7969dc1b1/build-script-build\n20.688  build-script-bu  237498 233581   0 /target/debug/build/markup5ever-31838724984befce/build-script-build\n20.733  rustc            237505 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name string_cache --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/string_cache-0.8.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"serde\" --cfg feature=\"serde_support\" ...\n20.749  as               237519 232780   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/644b6a24ae2ff5c1-blob_garbage_meter.o /tmp/ccGpont6.s\n20.927  cc               237593 237349   0 /tmp/native-trace-232648-1783993342344/shims/cc -m64 /target/debug/build/markup5ever-31838724984befce/rustcvyW1VW/symbols.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.00bugusk6670k49tcjhp371ib.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09or6hn0xtain3gkyopvciaz0.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09sxli55pm82xazi37z60169v.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0b7u0z26r89so21w6r1dksf6o.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0dvoqnvzwqw4gef85cqrcwblr.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0nrlwiynckpwo0gnfqgxlb5i5.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0qtoiy8zcntvir7a8lkyni6mr.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0rzuw3jj5qxboflpyrn14r4oy.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xmg0bm2ibunyeuzoj1b3b6rk.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xonkzg6bej7y03ibebgtt9b8.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1951ev2fh8qfq6v6atu5b5u0f.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1fq8ad0hcdujygb3gv350fju8.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1k15psoggxaxsgztj11cr3yxs.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1kbjez9nz1obex56s414wti6f.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.24hferydrrp2dmi07dhvubo6e.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2514ggscyvvp3o7z2icusuw1w.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2afw7f114lj0w3pa6qpqmoz5o.0sbxhge.rcgu.o ...\n20.963  rustc            237596 233581   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name markup5ever --edition=2018 lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=9b81bab69d0b6fbe ...\n21.018  riscv64-linux-g  237600 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n21.026  cc1plus          237603 237600   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n21.033  cc               237594 237593   0 /usr/bin/cc -m64 /target/debug/build/markup5ever-31838724984befce/rustcvyW1VW/symbols.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.00bugusk6670k49tcjhp371ib.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09or6hn0xtain3gkyopvciaz0.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09sxli55pm82xazi37z60169v.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0b7u0z26r89so21w6r1dksf6o.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0dvoqnvzwqw4gef85cqrcwblr.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0nrlwiynckpwo0gnfqgxlb5i5.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0qtoiy8zcntvir7a8lkyni6mr.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0rzuw3jj5qxboflpyrn14r4oy.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xmg0bm2ibunyeuzoj1b3b6rk.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xonkzg6bej7y03ibebgtt9b8.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1951ev2fh8qfq6v6atu5b5u0f.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1fq8ad0hcdujygb3gv350fju8.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1k15psoggxaxsgztj11cr3yxs.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1kbjez9nz1obex56s414wti6f.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.24hferydrrp2dmi07dhvubo6e.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2514ggscyvvp3o7z2icusuw1w.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2afw7f114lj0w3pa6qpqmoz5o.0sbxhge.rcgu.o ...\n21.059  collect2         237604 237594   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccokXueB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.060  ld.lld           237606 237604   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccokXueB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce ...\n21.062  rust-lld         237606 237604   0 \n21.264  rustc            237626 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name markup5ever --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/markup5ever-0.11.0/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0c85247d2b5ca5c4 ...\n21.374  build-script-bu  237649 234231   0 /target/debug/build/markup5ever-31838724984befce/build-script-build\n21.401  16               237662 1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n21.435  frpc             237662 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n21.626  rustc            237698 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/markup5ever-0.11.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=8e0b00d2b5a1934f ...\n21.675  rustc            237703 234231   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name markup5ever --edition=2018 lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=9fb4028d3fcfdc63 ...\n22.157  cc               237736 237698   0 /tmp/native-trace-235398-1783993350018/shims/cc -m64 /target/debug/build/markup5ever-a32dafa7969dc1b1/rustcVnUORh/symbols.o /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.0.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.1.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.2.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.7685p3eeoamip0z4pjuo4z4pe.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libstring_cache_codegen-226bca7e0be408b8.rlib /target/debug/deps/libquote-caa5a6f783f770e4.rlib /target/debug/deps/libproc_macro2-bcc52298e70ee541.rlib /target/debug/deps/libunicode_xid-bc2f9a71a9eadac1.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libphf_codegen-482db3ae92eb371b.rlib /target/debug/deps/libphf_generator-440742b73fd02201.rlib /target/debug/deps/librand-63ec678486dbfb81.rlib /target/debug/deps/librand_chacha-9e936d218899b44d.rlib /target/debug/deps/libppv_lite86-0a6ffb3623ef1b3c.rlib ...\n22.161  cc               237745 237736   0 /usr/bin/cc -m64 /target/debug/build/markup5ever-a32dafa7969dc1b1/rustcVnUORh/symbols.o /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.0.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.1.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.2.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.7685p3eeoamip0z4pjuo4z4pe.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libstring_cache_codegen-226bca7e0be408b8.rlib /target/debug/deps/libquote-caa5a6f783f770e4.rlib /target/debug/deps/libproc_macro2-bcc52298e70ee541.rlib /target/debug/deps/libunicode_xid-bc2f9a71a9eadac1.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libphf_codegen-482db3ae92eb371b.rlib /target/debug/deps/libphf_generator-440742b73fd02201.rlib /target/debug/deps/librand-63ec678486dbfb81.rlib /target/debug/deps/librand_chacha-9e936d218899b44d.rlib /target/debug/deps/libppv_lite86-0a6ffb3623ef1b3c.rlib ...\n22.167  collect2         237746 237745   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNl85kv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.175  ld.lld           237747 237746   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNl85kv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1 ...\n22.177  rust-lld         237747 237746   0 \n22.519  runc             237786 232416   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aec7b5f96dc6125e3c9d623e698cbb9a005a2a228f21fa301b39dfe20fb --log-format json --systemd-cgroup kill --all aec7b5f96dc6125e3c9d623e698cbb9a005a2a228f21fa301b39dfe20fbb451e 9\n22.533  runc             237792 232416   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aec7b5f96dc6125e3c9d623e698cbb9a005a2a228f21fa301b39dfe20fb --log-format json --systemd-cgroup delete aec7b5f96dc6125e3c9d623e698cbb9a005a2a228f21fa301b39dfe20fbb451e\n22.549  containerd-shim  237798 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id aec7b5f96dc6125e3c9d623e698cbb9a005a2a228f21fa301b39dfe20fbb451e -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aec7b5f96dc6125e3c9d623e698cbb9a005a2a228f21fa301b39dfe20fb delete\n22.555  runc             237804 237798   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aec7b5f96dc6125e3c9d623e698cbb9a005a2a228f21fa301b39dfe20fbb451 --log-format json delete --force aec7b5f96dc6125e3c9d623e698cbb9a005a2a228f21fa301b39dfe20fbb451e\n22.594  as               237810 230581   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/644b6a24ae2ff5c1-blob_file_cache.o /tmp/cctEzeyN.s\n22.606  systemd-sysctl   237812 237811   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth519ed85 --prefix=/net/ipv4/neigh/veth519ed85 --prefix=/net/ipv6/conf/veth519ed85 --prefix=/net/ipv6/neigh/veth519ed85\n22.640  build-script-bu  237816 236108   0 /target/debug/build/markup5ever-a32dafa7969dc1b1/build-script-build\n23.019  rustc            237871 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name string_cache --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/string_cache-0.8.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"serde\" --cfg feature=\"serde_support\" ...\n23.253  riscv64-linux-g  237883 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n23.263  cc1plus          237884 237883   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n23.318  rustc            237887 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name markup5ever --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/markup5ever-0.11.0/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=902d00bc7b6b8329 ...\n23.321  as               237888 232756   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/644b6a24ae2ff5c1-prefetch_buffer_collectio /tmp/ccsF5UY5.s\n23.413  runc             237893 231433   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e7210 --log-format json --systemd-cgroup kill --all 9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e721041d49 9\n23.429  as               237898 229459   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/644b6a24ae2ff5c1-blob_source.o /tmp/ccjEUA2P.s\n23.431  runc             237899 231895   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c6 --log-format json --systemd-cgroup kill --all 84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c60f58a 9\n23.440  runc             237906 231433   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e7210 --log-format json --systemd-cgroup delete 9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e721041d49\n23.458  runc             237913 231895   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c6 --log-format json --systemd-cgroup delete 84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c60f58a\n23.547  runc             237920 231634   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c0 --log-format json --systemd-cgroup kill --all c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c036fbb 9\n23.572  runc             237926 231634   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c0 --log-format json --systemd-cgroup delete c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c036fbb\n"
}
```

#### Record 15

```json
{
  "argv": [
    "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 232365,
  "build_script_target_dir": "pulldown-cmark-3bfaa0284ef6cd6a",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build-script-build",
  "pid": 232365,
  "ppid": 232015,
  "root_cargo_pid": 232015,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "_build_script_out_dir": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/out"
}
```

#### Record 16

```json
{
  "crate": "pulldown-cmark",
  "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "event_id": "bsrun:c87be39f98625358:7a6292397c2722f9:45329bbb65dbee50",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
  "out_dir": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
  "success": true,
  "target": null,
  "version": "0.13.0",
  "_owner": {
    "crate": "pulldown-cmark",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
    "source": "cwd_prefix"
  }
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T01:42:45.536916+00:00",
  "crate": "pulldown-cmark",
  "version": "0.13.0",
  "architecture": "ppc64le",
  "duration_seconds": 33.337092401925474,
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
        "manifest_path": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0/Cargo.toml"
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
      "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
      "workspace_root": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0"
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
          "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
          "name": "pulldown-cmark",
          "version": "0.13.0",
          "manifest_path": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0"
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 232258,
      "ppid": 232130,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
      "event_id": "used:cc:7f614eb0daeae15c:1661cb0a62de273a:154f8437eefadc83",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
      "pid": 232258,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
      "event_id": "used:cc:7f614eb0daeae15c:2a53e4393c7c814d:154f8437eefadc83",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
      "pid": 232258,
      "sha256": "d31c7e1d4b8ab3e8ed82153f77c66a05ecdd7dd7b213a31010d55de15857e91d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
      "event_id": "used:cc:7f614eb0daeae15c:7b83443f27ad00cd:154f8437eefadc83",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
      "pid": 232258,
      "sha256": "5fd587170252d77b20ffe09f58156b43afb28881c27e505ea7ca9aa0d4b7e6e2",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
      "event_id": "used:cc:7f614eb0daeae15c:a02501081a43c9d4:154f8437eefadc83",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
      "pid": 232258,
      "sha256": "bc54e3e2281719a8cd9fa152724bdaa0b2f6a4bcf34048625b2c97535796b6ff",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
      "event_id": "used:cc:7f614eb0daeae15c:a64f60427e586378:154f8437eefadc83",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
      "pid": 232258,
      "sha256": "3f48625142798e15e093ede66eefbfc14a18ba73a6c55326a8c9ecaba3990277",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
      "event_id": "used:cc:7f614eb0daeae15c:fa0a4721983e273f:154f8437eefadc83",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
      "pid": 232258,
      "sha256": "bbb6c5eae70af173367a9cc072f67f4805e488e5260c15f04427db52ff957f78",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
      "event_id": "used:cc:7f614eb0daeae15c:312519c4a59779fc:154f8437eefadc83",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a",
      "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
      "pid": 232258,
      "sha256": "a4914eb4d43ad45db892635f72dd262e44cb35a20e5a76b2a5ff53c9a3de75b6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
      "cargo_pkg_name": "pulldown-cmark",
      "cargo_pkg_version": "0.13.0",
      "context_path": "/tmp/native-trace-230411-1783993336672/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-230411-1783993336672/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 232258,
      "ppid": 232130,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj",
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
          "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj",
          "kind": "object",
          "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/rustcwGElOj/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
          "kind": "object",
          "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.24p2lkby2lkjvcii1qdg7rdiu.1mg1vkq.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
          "kind": "object",
          "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.56te0vhmey4bctsxqc7x2w4pl.1mg1vkq.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
          "kind": "object",
          "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.am6ezy8y3buctp4u7bttlvxsv.1mg1vkq.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
          "kind": "object",
          "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.c4xfn6zb3mdilyjp6q8eye1wn.1mg1vkq.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
          "kind": "object",
          "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.dh65drbm2keudw4yl92ub3ewc.1mg1vkq.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a",
          "kind": "object",
          "path": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build_script_build-3bfaa0284ef6cd6a.43aazc5zrgg3qkz3xvv130ph2.1mg1vkq.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-232258-1783993341497649568.map",
      "pid": 232258,
      "ppid": 232130,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-232258-1783993341497649568.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
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
      "parsed_event_count": 1056,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1057,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "dex.crates.io-1949cf8c6b5b557f/getrandom-0.2.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"custom\", \"js\", \"js-sys\", \"rdrand\", \"rustc-dep-of-std\", \"std\", \"test-in-browser ...\n16.466  build-script-bu  236681 236108   0 /target/debug/build/serde-cc51c28a4bad2951/build-script-build\n16.475  rustc            236683 236681   0 \n16.603  rustc            236695 236108   0 \n16.619  rustc            236696 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand_core --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"getrandom\" --cfg feature=\"std\" ...\n16.659  rustc            236701 233032   0 \n16.673  rustc            236708 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot-0.12.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arc_lock\", \"deadlock_detection\", \"default\", \"hardware-lock-elision\", \"nightly\", \"owning_ref\", \"send_guard\", ...\n16.702  rustc            236718 233032   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand_chacha --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"serde\", \"serde1\", \"simd\", \"std\")) ...\n16.735  as               236731 229553   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/644b6a24ae2ff5c1-blob_fetcher.o /tmp/cckbePrT.s\n16.739  powerpc64le-lin  236723 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n16.748  cc1plus          236733 236723   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n16.808  runc             236737 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2639903245 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n16.820  riscv64-linux-g  236744 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n16.823  exe              236746 236737   0 /proc/self/exe init\n16.846  cc1plus          236747 236744   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n16.874  curl             236751 236737   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n16.916  rustc            236764 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.17/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n16.942  rustc            236768 233032   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"getrandom\" ...\n16.964  rustc            236738 234231   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name string_cache --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/string_cache-0.8.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"serde\" --cfg feature=\"serde_support\" ...\n16.971  rustc            236781 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand_chacha --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"serde\", \"serde1\", \"simd\", \"std\")) ...\n17.179  rustc            236801 233581   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ppv_lite86 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.21/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"simd\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n17.265  sh               236814 2147557   0 /bin/sh -c which ps\n17.267  which            236814 2147557   0 /usr/bin/which ps\n17.271  sh               236817 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.273  ps               236817 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.282  rustc            236816 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"getrandom\" ...\n17.337  sh               236823 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n17.337  cpuUsage.sh      236823 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n17.342  sed              236825 236823   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.346  cat              236827 236823   0 \n17.346  cat              236826 236823   0 /usr/bin/cat /proc/2240539/stat\n17.347  sleep            236828 236823   0 /usr/bin/sleep 1\n17.426  as               236834 229094   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/644b6a24ae2ff5c1-blob_fetcher.o /tmp/ccbIqYrb.s\n17.444  rustc            236833 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.17/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n17.539  rustc            236842 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot_core --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot_core-0.9.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"backtrace\", \"deadlock_detection\", \"nightly\", \"petgraph\", \"thread-id\")) -C metadata=ba2ec95b61885fb8 ...\n17.696  rustc            236851 233581   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand_chacha --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"serde\", \"serde1\", \"simd\", \"std\")) ...\n17.715  rustc            236856 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-1.0.89/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n17.823  rustc            236869 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-1.0.89/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n17.925  rustc            236877 233581   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"getrandom\" ...\n17.973  rustc            236887 234231   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ppv_lite86 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.21/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"simd\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n17.976  rustc            236893 233032   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_generator --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.10.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"criterion\")) -C metadata=33cbcd4cf8bd70f8 ...\n17.986  rustc            236895 233032   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_generator --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.11.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"criterion\")) -C metadata=9b0d7500eeb5b8d5 ...\n17.990  rustc            236901 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name getrandom --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"custom\", \"js\", \"js-sys\", \"rdrand\", \"rustc-dep-of-std\", \"std\", \"test-in-browser ...\n18.071  rustc            236917 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot-0.12.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arc_lock\", \"deadlock_detection\", \"default\", \"hardware-lock-elision\", \"nightly\", \"owning_ref\", \"send_guard\", ...\n18.107  rustc            236920 233032   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_codegen --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.10.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=83b98398b575e289 ...\n18.134  rustc            236931 233032   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name string_cache_codegen --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/string_cache_codegen-0.5.4/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=1dea28fdcb7dc932 ...\n18.161  rustc            236938 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand_core --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"getrandom\" --cfg feature=\"std\" ...\n18.346  rustc            236954 234231   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand_chacha --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"serde\", \"serde1\", \"simd\", \"std\")) ...\n18.350  sed              236956 236823   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.354  cat              236957 236823   0 /usr/bin/cat /proc/2240539/stat\n18.356  cat              236959 236823   0 /usr/bin/cat /proc/4193716/stat\n18.405  riscv64-linux-g  236964 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n18.407  as               236965 229519   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/40a8ecc0aa07be2f-cache.o /tmp/ccT8xf0j.s\n18.443  cc1plus          236966 236964   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n18.542  rustc            236975 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_generator --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.10.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"criterion\")) -C metadata=905fcc6afc71b676 ...\n18.565  rustc            236984 234231   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"getrandom\" ...\n18.612  rustc            236998 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_codegen --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.10.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=93b54f05441d9d5f ...\n18.621  rustc            237000 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand_chacha --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"serde\", \"serde1\", \"simd\", \"std\")) ...\n18.635  rustc            237001 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name string_cache_codegen --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/string_cache_codegen-0.5.2/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=947e25622fb6be5b ...\n18.806  rustc            237026 233581   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_generator --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.10.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"criterion\")) -C metadata=33cbcd4cf8bd70f8 ...\n18.811  rustc            237027 233581   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_generator --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.11.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"criterion\")) -C metadata=9b0d7500eeb5b8d5 ...\n18.837  rustc            237018 233032   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=d1b9fd6f7f6cda03 ...\n18.950  aarch64-linux-g  237042 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n18.961  cc1plus          237043 237042   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n18.994  rustc            237048 233581   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_codegen --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.10.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=83b98398b575e289 ...\n19.035  rustc            237056 233581   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name string_cache_codegen --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/string_cache_codegen-0.5.4/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=1dea28fdcb7dc932 ...\n19.224  rustc            237085 236108   0 \n19.387  rustc            237151 234231   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_generator --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.11.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"criterion\")) -C metadata=9b0d7500eeb5b8d5 ...\n19.454  rustc            237152 234231   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_generator --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.10.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"criterion\")) -C metadata=33cbcd4cf8bd70f8 ...\n19.496  cc               237213 237018   0 /tmp/native-trace-231948-1783993341078/shims/cc -m64 /target/debug/build/markup5ever-31838724984befce/rustcvc0mDI/symbols.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.00bugusk6670k49tcjhp371ib.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09or6hn0xtain3gkyopvciaz0.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09sxli55pm82xazi37z60169v.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0b7u0z26r89so21w6r1dksf6o.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0dvoqnvzwqw4gef85cqrcwblr.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0nrlwiynckpwo0gnfqgxlb5i5.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0qtoiy8zcntvir7a8lkyni6mr.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0rzuw3jj5qxboflpyrn14r4oy.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xmg0bm2ibunyeuzoj1b3b6rk.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xonkzg6bej7y03ibebgtt9b8.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1951ev2fh8qfq6v6atu5b5u0f.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1fq8ad0hcdujygb3gv350fju8.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1k15psoggxaxsgztj11cr3yxs.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1kbjez9nz1obex56s414wti6f.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.24hferydrrp2dmi07dhvubo6e.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2514ggscyvvp3o7z2icusuw1w.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2afw7f114lj0w3pa6qpqmoz5o.1qkk8go.rcgu.o ...\n19.503  cc               237214 237213   0 /usr/bin/cc -m64 /target/debug/build/markup5ever-31838724984befce/rustcvc0mDI/symbols.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.00bugusk6670k49tcjhp371ib.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09or6hn0xtain3gkyopvciaz0.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09sxli55pm82xazi37z60169v.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0b7u0z26r89so21w6r1dksf6o.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0dvoqnvzwqw4gef85cqrcwblr.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0nrlwiynckpwo0gnfqgxlb5i5.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0qtoiy8zcntvir7a8lkyni6mr.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0rzuw3jj5qxboflpyrn14r4oy.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xmg0bm2ibunyeuzoj1b3b6rk.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xonkzg6bej7y03ibebgtt9b8.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1951ev2fh8qfq6v6atu5b5u0f.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1fq8ad0hcdujygb3gv350fju8.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1k15psoggxaxsgztj11cr3yxs.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1kbjez9nz1obex56s414wti6f.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.24hferydrrp2dmi07dhvubo6e.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2514ggscyvvp3o7z2icusuw1w.1qkk8go.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2afw7f114lj0w3pa6qpqmoz5o.1qkk8go.rcgu.o ...\n19.511  collect2         237216 237214   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1Iil2b.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.518  ld.lld           237221 237216   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1Iil2b.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce ...\n19.524  rust-lld         237221 237216   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc1Iil2b.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.531  rustc            237222 234231   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_codegen --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.10.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=83b98398b575e289 ...\n19.603  rustc            237248 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/markup5ever-0.11.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=8e0b00d2b5a1934f ...\n19.630  rustc            237253 233581   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=d1b9fd6f7f6cda03 ...\n19.704  rustc            237263 234231   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name string_cache_codegen --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/string_cache_codegen-0.5.4/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=1dea28fdcb7dc932 ...\n19.824  build-script-bu  237270 233032   0 /target/debug/build/markup5ever-31838724984befce/build-script-build\n19.978  riscv64-linux-g  237273 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n19.983  cc1plus          237274 237273   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n20.136  rustc            237307 233032   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name markup5ever --edition=2018 lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=25728beef10be373 ...\n20.223  rustc            237337 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_generator --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.10.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"criterion\")) -C metadata=905fcc6afc71b676 ...\n20.233  rustc            237349 234231   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=d1b9fd6f7f6cda03 ...\n20.239  cc               237353 237248   0 /tmp/native-trace-235020-1783993349143/shims/cc -m64 /target/debug/build/markup5ever-a32dafa7969dc1b1/rustcUcQ8pz/symbols.o /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.0.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.1.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.2.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.7685p3eeoamip0z4pjuo4z4pe.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libstring_cache_codegen-226bca7e0be408b8.rlib /target/debug/deps/libquote-caa5a6f783f770e4.rlib /target/debug/deps/libproc_macro2-bcc52298e70ee541.rlib /target/debug/deps/libunicode_xid-bc2f9a71a9eadac1.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libphf_codegen-482db3ae92eb371b.rlib /target/debug/deps/libphf_generator-440742b73fd02201.rlib /target/debug/deps/librand-63ec678486dbfb81.rlib /target/debug/deps/librand_chacha-9e936d218899b44d.rlib /target/debug/deps/libppv_lite86-0a6ffb3623ef1b3c.rlib ...\n20.241  cc               237363 237353   0 /usr/bin/cc -m64 /target/debug/build/markup5ever-a32dafa7969dc1b1/rustcUcQ8pz/symbols.o /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.0.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.1.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.2.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.7685p3eeoamip0z4pjuo4z4pe.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libstring_cache_codegen-226bca7e0be408b8.rlib /target/debug/deps/libquote-caa5a6f783f770e4.rlib /target/debug/deps/libproc_macro2-bcc52298e70ee541.rlib /target/debug/deps/libunicode_xid-bc2f9a71a9eadac1.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libphf_codegen-482db3ae92eb371b.rlib /target/debug/deps/libphf_generator-440742b73fd02201.rlib /target/debug/deps/librand-63ec678486dbfb81.rlib /target/debug/deps/librand_chacha-9e936d218899b44d.rlib /target/debug/deps/libppv_lite86-0a6ffb3623ef1b3c.rlib ...\n20.248  collect2         237367 237363   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWNi5xt.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n20.259  ld.lld           237376 237367   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWNi5xt.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1 ...\n20.262  rust-lld         237376 237367   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWNi5xt.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n20.372  cc               237420 237253   0 /tmp/native-trace-232600-1783993342102/shims/cc -m64 /target/debug/build/markup5ever-31838724984befce/rustcl6ISXW/symbols.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.00bugusk6670k49tcjhp371ib.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09or6hn0xtain3gkyopvciaz0.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09sxli55pm82xazi37z60169v.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0b7u0z26r89so21w6r1dksf6o.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0dvoqnvzwqw4gef85cqrcwblr.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0nrlwiynckpwo0gnfqgxlb5i5.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0qtoiy8zcntvir7a8lkyni6mr.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0rzuw3jj5qxboflpyrn14r4oy.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xmg0bm2ibunyeuzoj1b3b6rk.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xonkzg6bej7y03ibebgtt9b8.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1951ev2fh8qfq6v6atu5b5u0f.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1fq8ad0hcdujygb3gv350fju8.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1k15psoggxaxsgztj11cr3yxs.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1kbjez9nz1obex56s414wti6f.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.24hferydrrp2dmi07dhvubo6e.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2514ggscyvvp3o7z2icusuw1w.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2afw7f114lj0w3pa6qpqmoz5o.0v8v8hx.rcgu.o ...\n20.377  cc               237437 237420   0 /usr/bin/cc -m64 /target/debug/build/markup5ever-31838724984befce/rustcl6ISXW/symbols.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.00bugusk6670k49tcjhp371ib.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09or6hn0xtain3gkyopvciaz0.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09sxli55pm82xazi37z60169v.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0b7u0z26r89so21w6r1dksf6o.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0dvoqnvzwqw4gef85cqrcwblr.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0nrlwiynckpwo0gnfqgxlb5i5.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0qtoiy8zcntvir7a8lkyni6mr.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0rzuw3jj5qxboflpyrn14r4oy.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xmg0bm2ibunyeuzoj1b3b6rk.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xonkzg6bej7y03ibebgtt9b8.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1951ev2fh8qfq6v6atu5b5u0f.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1fq8ad0hcdujygb3gv350fju8.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1k15psoggxaxsgztj11cr3yxs.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1kbjez9nz1obex56s414wti6f.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.24hferydrrp2dmi07dhvubo6e.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2514ggscyvvp3o7z2icusuw1w.0v8v8hx.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2afw7f114lj0w3pa6qpqmoz5o.0v8v8hx.rcgu.o ...\n20.394  collect2         237438 237437   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cch4dzx2.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n20.399  ld.lld           237439 237438   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cch4dzx2.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce ...\n20.404  rust-lld         237439 237438   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cch4dzx2.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n20.495  rustc            237462 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name string_cache_codegen --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/string_cache_codegen-0.5.2/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=947e25622fb6be5b ...\n20.495  rustc            237461 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_codegen --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.10.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=93b54f05441d9d5f ...\n20.575  build-script-bu  237476 235832   0 /target/debug/build/markup5ever-a32dafa7969dc1b1/build-script-build\n20.688  build-script-bu  237498 233581   0 /target/debug/build/markup5ever-31838724984befce/build-script-build\n20.733  rustc            237505 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name string_cache --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/string_cache-0.8.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"serde\" --cfg feature=\"serde_support\" ...\n20.749  as               237519 232780   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/644b6a24ae2ff5c1-blob_garbage_meter.o /tmp/ccGpont6.s\n20.927  cc               237593 237349   0 /tmp/native-trace-232648-1783993342344/shims/cc -m64 /target/debug/build/markup5ever-31838724984befce/rustcvyW1VW/symbols.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.00bugusk6670k49tcjhp371ib.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09or6hn0xtain3gkyopvciaz0.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09sxli55pm82xazi37z60169v.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0b7u0z26r89so21w6r1dksf6o.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0dvoqnvzwqw4gef85cqrcwblr.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0nrlwiynckpwo0gnfqgxlb5i5.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0qtoiy8zcntvir7a8lkyni6mr.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0rzuw3jj5qxboflpyrn14r4oy.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xmg0bm2ibunyeuzoj1b3b6rk.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xonkzg6bej7y03ibebgtt9b8.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1951ev2fh8qfq6v6atu5b5u0f.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1fq8ad0hcdujygb3gv350fju8.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1k15psoggxaxsgztj11cr3yxs.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1kbjez9nz1obex56s414wti6f.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.24hferydrrp2dmi07dhvubo6e.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2514ggscyvvp3o7z2icusuw1w.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2afw7f114lj0w3pa6qpqmoz5o.0sbxhge.rcgu.o ...\n20.963  rustc            237596 233581   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name markup5ever --edition=2018 lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=9b81bab69d0b6fbe ...\n21.018  riscv64-linux-g  237600 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n21.026  cc1plus          237603 237600   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n21.033  cc               237594 237593   0 /usr/bin/cc -m64 /target/debug/build/markup5ever-31838724984befce/rustcvyW1VW/symbols.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.00bugusk6670k49tcjhp371ib.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09or6hn0xtain3gkyopvciaz0.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.09sxli55pm82xazi37z60169v.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0b7u0z26r89so21w6r1dksf6o.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0dvoqnvzwqw4gef85cqrcwblr.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0nrlwiynckpwo0gnfqgxlb5i5.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0qtoiy8zcntvir7a8lkyni6mr.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0rzuw3jj5qxboflpyrn14r4oy.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xmg0bm2ibunyeuzoj1b3b6rk.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.0xonkzg6bej7y03ibebgtt9b8.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1951ev2fh8qfq6v6atu5b5u0f.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1fq8ad0hcdujygb3gv350fju8.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1k15psoggxaxsgztj11cr3yxs.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.1kbjez9nz1obex56s414wti6f.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.24hferydrrp2dmi07dhvubo6e.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2514ggscyvvp3o7z2icusuw1w.0sbxhge.rcgu.o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce.2afw7f114lj0w3pa6qpqmoz5o.0sbxhge.rcgu.o ...\n21.059  collect2         237604 237594   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccokXueB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.060  ld.lld           237606 237604   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccokXueB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/markup5ever-31838724984befce/build_script_build-31838724984befce ...\n21.062  rust-lld         237606 237604   0 \n21.264  rustc            237626 235832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name markup5ever --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/markup5ever-0.11.0/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0c85247d2b5ca5c4 ...\n21.374  build-script-bu  237649 234231   0 /target/debug/build/markup5ever-31838724984befce/build-script-build\n21.401  16               237662 1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n21.435  frpc             237662 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n21.626  rustc            237698 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/markup5ever-0.11.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=8e0b00d2b5a1934f ...\n21.675  rustc            237703 234231   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name markup5ever --edition=2018 lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=9fb4028d3fcfdc63 ...\n22.157  cc               237736 237698   0 /tmp/native-trace-235398-1783993350018/shims/cc -m64 /target/debug/build/markup5ever-a32dafa7969dc1b1/rustcVnUORh/symbols.o /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.0.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.1.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.2.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.7685p3eeoamip0z4pjuo4z4pe.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libstring_cache_codegen-226bca7e0be408b8.rlib /target/debug/deps/libquote-caa5a6f783f770e4.rlib /target/debug/deps/libproc_macro2-bcc52298e70ee541.rlib /target/debug/deps/libunicode_xid-bc2f9a71a9eadac1.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libphf_codegen-482db3ae92eb371b.rlib /target/debug/deps/libphf_generator-440742b73fd02201.rlib /target/debug/deps/librand-63ec678486dbfb81.rlib /target/debug/deps/librand_chacha-9e936d218899b44d.rlib /target/debug/deps/libppv_lite86-0a6ffb3623ef1b3c.rlib ...\n22.161  cc               237745 237736   0 /usr/bin/cc -m64 /target/debug/build/markup5ever-a32dafa7969dc1b1/rustcVnUORh/symbols.o /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.0.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.1.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.build_script_build.a6b425061977af17-cgu.2.r /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1.7685p3eeoamip0z4pjuo4z4pe.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libstring_cache_codegen-226bca7e0be408b8.rlib /target/debug/deps/libquote-caa5a6f783f770e4.rlib /target/debug/deps/libproc_macro2-bcc52298e70ee541.rlib /target/debug/deps/libunicode_xid-bc2f9a71a9eadac1.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libphf_codegen-482db3ae92eb371b.rlib /target/debug/deps/libphf_generator-440742b73fd02201.rlib /target/debug/deps/librand-63ec678486dbfb81.rlib /target/debug/deps/librand_chacha-9e936d218899b44d.rlib /target/debug/deps/libppv_lite86-0a6ffb3623ef1b3c.rlib ...\n22.167  collect2         237746 237745   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNl85kv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n22.175  ld.lld           237747 237746   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNl85kv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/markup5ever-a32dafa7969dc1b1/build_script_build-a32dafa7969dc1b1 ...\n22.177  rust-lld         237747 237746   0 \n22.519  runc             237786 232416   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aec7b5f96dc6125e3c9d623e698cbb9a005a2a228f21fa301b39dfe20fb --log-format json --systemd-cgroup kill --all aec7b5f96dc6125e3c9d623e698cbb9a005a2a228f21fa301b39dfe20fbb451e 9\n22.533  runc             237792 232416   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aec7b5f96dc6125e3c9d623e698cbb9a005a2a228f21fa301b39dfe20fb --log-format json --systemd-cgroup delete aec7b5f96dc6125e3c9d623e698cbb9a005a2a228f21fa301b39dfe20fbb451e\n22.549  containerd-shim  237798 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id aec7b5f96dc6125e3c9d623e698cbb9a005a2a228f21fa301b39dfe20fbb451e -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aec7b5f96dc6125e3c9d623e698cbb9a005a2a228f21fa301b39dfe20fb delete\n22.555  runc             237804 237798   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aec7b5f96dc6125e3c9d623e698cbb9a005a2a228f21fa301b39dfe20fbb451 --log-format json delete --force aec7b5f96dc6125e3c9d623e698cbb9a005a2a228f21fa301b39dfe20fbb451e\n22.594  as               237810 230581   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/644b6a24ae2ff5c1-blob_file_cache.o /tmp/cctEzeyN.s\n22.606  systemd-sysctl   237812 237811   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth519ed85 --prefix=/net/ipv4/neigh/veth519ed85 --prefix=/net/ipv6/conf/veth519ed85 --prefix=/net/ipv6/neigh/veth519ed85\n22.640  build-script-bu  237816 236108   0 /target/debug/build/markup5ever-a32dafa7969dc1b1/build-script-build\n23.019  rustc            237871 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name string_cache --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/string_cache-0.8.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"serde\" --cfg feature=\"serde_support\" ...\n23.253  riscv64-linux-g  237883 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n23.263  cc1plus          237884 237883   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n23.318  rustc            237887 236108   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name markup5ever --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/markup5ever-0.11.0/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=902d00bc7b6b8329 ...\n23.321  as               237888 232756   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/644b6a24ae2ff5c1-prefetch_buffer_collectio /tmp/ccsF5UY5.s\n23.413  runc             237893 231433   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e7210 --log-format json --systemd-cgroup kill --all 9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e721041d49 9\n23.429  as               237898 229459   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/644b6a24ae2ff5c1-blob_source.o /tmp/ccjEUA2P.s\n23.431  runc             237899 231895   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c6 --log-format json --systemd-cgroup kill --all 84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c60f58a 9\n23.440  runc             237906 231433   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e7210 --log-format json --systemd-cgroup delete 9e5dfe0de7e3521a54ef28301e5ea503d675dfe167efb2b104e856e721041d49\n23.458  runc             237913 231895   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c6 --log-format json --systemd-cgroup delete 84226a9e4a04288f0d6fdde439bb29a449735e4647fee646d813b33f4c60f58a\n23.547  runc             237920 231634   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c0 --log-format json --systemd-cgroup kill --all c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c036fbb 9\n23.572  runc             237926 231634   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c0 --log-format json --systemd-cgroup delete c41273983b0044fa4e9f7e50f45f87ad3ea0b90b1daee624646e3f9c0c036fbb\n"
    },
    {
      "argv": [
        "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 232365,
      "build_script_target_dir": "pulldown-cmark-3bfaa0284ef6cd6a",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build-script-build",
      "pid": 232365,
      "ppid": 232015,
      "root_cargo_pid": 232015,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "pulldown-cmark",
      "cwd": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
      "event_id": "bsrun:c87be39f98625358:7a6292397c2722f9:45329bbb65dbee50",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
      "out_dir": "/target/debug/build/pulldown-cmark-3bfaa0284ef6cd6a/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
      "success": true,
      "target": null,
      "version": "0.13.0",
      "_owner": {
        "crate": "pulldown-cmark",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0#pulldown-cmark@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-1ehe2d0p/src/pulldown-cmark-0.13.0",
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
