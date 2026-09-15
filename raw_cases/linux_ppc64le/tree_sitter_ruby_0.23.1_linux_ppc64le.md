# `tree-sitter-ruby` `0.23.1`

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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
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
  "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
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
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-1039886-1783999161964209769.map",
  "pid": 1039886,
  "ppid": 1039845,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1039886-1783999161964209769.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/libtree-sitter-ruby.a`

Owner: `tree-sitter-ruby` `0.23.1`

### Source files

* `/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1/src/parser.c`
* `/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1/src/scanner.c`

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
    "-std=c11",
    "-I",
    "src",
    "-Wall",
    "-Wextra",
    "-Wno-unused-value",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-parser.o",
    "-c",
    "src/parser.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039962,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 1039994,
  "ppid": 1039962,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "-std=c11",
    "-I",
    "src",
    "-Wall",
    "-Wextra",
    "-Wno-unused-value",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-scanner.o",
    "-c",
    "src/scanner.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039962,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 1041224,
  "ppid": 1039962,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "src",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "src/scanner.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "scanner.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-scanner.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "..."
  ],
  "src": "src/scanner.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-scanner.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 1041225,
  "ppid": 1041224,
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "root_cargo_pid": 1039017,
  "build_script_root_pid": 1039962,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
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
    "src",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "src/parser.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "parser.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-parser.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "..."
  ],
  "src": "src/parser.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-parser.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 1039997,
  "ppid": 1039994,
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "root_cargo_pid": 1039017,
  "build_script_root_pid": 1039962,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
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
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/libtree-sitter-ruby.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-parser.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-scanner.o"
  ],
  "archive": "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/libtree-sitter-ruby.a",
  "objects": [
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-parser.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-scanner.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 1041258,
  "ppid": 1039962,
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "root_cargo_pid": 1039017,
  "build_script_root_pid": 1039962,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
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
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "workspace_root": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
      "name": "cc",
      "version": "1.2.67",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
      "name": "find-msvc-tools",
      "version": "0.1.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
      "name": "memchr",
      "version": "2.8.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
      "name": "shlex",
      "version": "2.0.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#streaming-iterator@0.1.9",
      "name": "streaming-iterator",
      "version": "0.1.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/streaming-iterator-0.1.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/streaming-iterator-0.1.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter@0.24.7",
      "name": "tree-sitter",
      "version": "0.24.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-0.24.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-0.24.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
      "name": "tree-sitter-language",
      "version": "0.1.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7"
    },
    {
      "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
      "name": "tree-sitter-ruby",
      "version": "0.23.1",
      "manifest_path": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1"
    }
  ],
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/symbols.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "exit_code": 0,
  "kind": "exec",
  "pid": 1039115,
  "ppid": 1039045,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-language",
    "version": "0.1.7",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/symbols.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-language",
  "cargo_pkg_version": "0.1.7",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "event_id": "used:cc:d9861ad91616b5cc:82817ea9f0745c96:085e3bf50b18abef",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
  "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/symbols.o",
  "pid": 1039115,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-language",
    "version": "0.1.7",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/symbols.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-language",
  "cargo_pkg_version": "0.1.7",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "event_id": "used:cc:d9861ad91616b5cc:04d242bb52149c08:085e3bf50b18abef",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
  "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
  "pid": 1039115,
  "sha256": "da99707d1d8127a1f25af4f3ba373e5e750453a5f3cf905bff78742f1d51481e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-language",
    "version": "0.1.7",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/symbols.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-language",
  "cargo_pkg_version": "0.1.7",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "event_id": "used:cc:d9861ad91616b5cc:22a29f0d0c58fcfa:085e3bf50b18abef",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
  "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
  "pid": 1039115,
  "sha256": "77ac94236c6fa2d2c7f071d002442abdff45a87fd63834eafb9403a64fea154d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-language",
    "version": "0.1.7",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/symbols.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/symbols.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/raw-dylibs",
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
  "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-language",
    "version": "0.1.7",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/symbols.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "cargo_pkg_name": "tree-sitter-language",
  "cargo_pkg_version": "0.1.7",
  "context_path": "/tmp/native-trace-1038682-1783999157895/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-1038682-1783999157895/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 1039115,
  "ppid": 1039045,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_owner": {
    "crate": "tree-sitter-language",
    "version": "0.1.7",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/symbols.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2",
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
      "directory": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-1039115-1783999160316033243.map",
  "pid": 1039115,
  "ppid": 1039045,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1039115-1783999160316033243.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "tree-sitter-language",
    "version": "0.1.7",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "exit_code": 0,
  "kind": "exec",
  "pid": 1039886,
  "ppid": 1039845,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-ruby",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "event_id": "used:cc:c07c8c8af6666626:a4931358f891e754:eb2d13ccf491a7e4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
  "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
  "pid": 1039886,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-ruby",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "event_id": "used:cc:c07c8c8af6666626:439a9f3debb82834:eb2d13ccf491a7e4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
  "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
  "pid": 1039886,
  "sha256": "7c2c8d7a9e88e9d920fe9bb35f5d8329bc2fa01b4b9a1f9f77609d93d833b37a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-ruby",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "event_id": "used:cc:c07c8c8af6666626:29204fff3d3f2419:eb2d13ccf491a7e4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
  "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
  "pid": 1039886,
  "sha256": "f75d4281c02642d0ad586179ee11c63f34983f342f1d754ddabeddcd932da3c2",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-ruby",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "event_id": "used:cc:c07c8c8af6666626:167f7a4dbe9dac96:eb2d13ccf491a7e4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
  "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
  "pid": 1039886,
  "sha256": "736297d8a4b342d74bdf07a1168f68aa0f588fb99b006524192070f0ce3c4c68",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-ruby",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "event_id": "used:cc:c07c8c8af6666626:309f4f7b75215560:eb2d13ccf491a7e4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
  "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
  "pid": 1039886,
  "sha256": "23b7ced54cfc2de5e097e1a75322e9e68a9f89dfe8c32351e552ab475cccb3be",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-ruby",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "event_id": "used:cc:c07c8c8af6666626:7ad2963acb00200d:eb2d13ccf491a7e4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
  "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
  "pid": 1039886,
  "sha256": "9ca1d2b9c72295ed5dece6525666f32cc8e1786a825f8691403e3f1fd5b7cdc4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-ruby",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "event_id": "used:cc:c07c8c8af6666626:e50029fc7f53dcc4:eb2d13ccf491a7e4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
  "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
  "pid": 1039886,
  "sha256": "c0985357418e67a5b05094601c0b8c5fdbaa79f26d2c52976084dfc0e9766c12",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-ruby",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "event_id": "used:cc:c07c8c8af6666626:a3c171880e82c55a:eb2d13ccf491a7e4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
  "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
  "pid": 1039886,
  "sha256": "1ceca619e7f7b7e56150caa61e6a38691ba9de60746bb9167432992da867b7b3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-ruby",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "event_id": "used:cc:c07c8c8af6666626:b50148b77213cc07:eb2d13ccf491a7e4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
  "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
  "pid": 1039886,
  "sha256": "0afd3eb636a678d855fb917cd187c3648b23dc4d1228f4d8e1efdf5d780a02f5",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-ruby",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "event_id": "used:cc:c07c8c8af6666626:9bb3af152572cbbd:eb2d13ccf491a7e4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
  "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
  "pid": 1039886,
  "sha256": "07a8e471ff1955076a857ebcd609163f95da42c38a86cb4d1e25e30775f5b9d5",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-ruby",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "event_id": "used:cc:c07c8c8af6666626:efc3111a30b0d4d8:eb2d13ccf491a7e4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
  "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
  "pid": 1039886,
  "sha256": "aab7dba120c228dbfbfdb47a9560edca62c518058f879c27e7b3c3f2e8f34f76",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-ruby",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "event_id": "used:cc:c07c8c8af6666626:4608b7f6b260db60:eb2d13ccf491a7e4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
  "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
  "pid": 1039886,
  "sha256": "5e3ca6c3f1ba4cdaec1cab961ee9b7c15a37432d6b1146dccd953695a3fb38a1",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-ruby",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "event_id": "used:cc:c07c8c8af6666626:b61fb8385f86f263:eb2d13ccf491a7e4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
  "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
  "pid": 1039886,
  "sha256": "8e9fcdfe4a5e81837f4ccd860ef68675202667939414402059f7a36efa8afcbf",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
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
  "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "cargo_pkg_name": "tree-sitter-ruby",
  "cargo_pkg_version": "0.23.1",
  "context_path": "/tmp/native-trace-1038682-1783999157895/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-1038682-1783999157895/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 1039886,
  "ppid": 1039845,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC",
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
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
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-1039886-1783999161964209769.map",
  "pid": 1039886,
  "ppid": 1039845,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1039886-1783999161964209769.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 26

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

#### Record 27

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 1,
  "parsed_event_count": 1315,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1316,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "r- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n18.981  collect2         1046557 1046552   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccrb954z.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libproc_macro_error_attr-c0f372eb48247273.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcvuYn6R/raw-dylibs ...\n18.986  ld.lld           1046561 1046557   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccrb954z.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr-c0f372eb48247273.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcvuYn6R/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.990  rust-lld         1046561 1046557   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccrb954z.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr-c0f372eb48247273.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n18.998  cc               1046562 1046508   0 /tmp/native-trace-1044207-1783999172017/shims/cc -m64 /target/debug/build/gtk-c9fea2000bcdf02d/rustcIuaB6N/symbols.o /target/debug/build/gtk-c9fea2000bcdf02d/build_script_build-c9fea2000bcdf02d.build_script_build.96c7cbeb8cc76ef-cgu.0.rcgu.o /target/debug/build/gtk-c9fea2000bcdf02d/build_script_build-c9fea2000bcdf02d.94w0fhu215livx365ryijbq3u.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libpkg_config-60dc64799e6cfcae.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.001  cc               1046566 1046562   0 /usr/bin/cc -m64 /target/debug/build/gtk-c9fea2000bcdf02d/rustcIuaB6N/symbols.o /target/debug/build/gtk-c9fea2000bcdf02d/build_script_build-c9fea2000bcdf02d.build_script_build.96c7cbeb8cc76ef-cgu.0.rcgu.o /target/debug/build/gtk-c9fea2000bcdf02d/build_script_build-c9fea2000bcdf02d.94w0fhu215livx365ryijbq3u.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libpkg_config-60dc64799e6cfcae.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.007  collect2         1046568 1046566   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRIxxKA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.014  rustc            1046567 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anyhow-1.0.95/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n19.022  ld.lld           1046570 1046568   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRIxxKA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gtk-c9fea2000bcdf02d/build_script_build-c9fea2000bcdf02d ...\n19.025  rust-lld         1046570 1046568   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRIxxKA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.042  rustc            1046590 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_conv --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-conv-0.1.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unused --warn=unreachable-pub --deny=clippy::std-instead-of-core --warn=missing-docs --deny=clippy::alloc-instead-of-core --check-cfg ...\n19.108  rustc            1046617 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/field-offset-0.3.6/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=927ca445b27343e0 ...\n19.139  rustc            1046631 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bitflags --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"default\", \"example_generated\", \"rustc-dep-of-std\")) ...\n19.143  rustc            1046634 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-error-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"syn\" --cfg feature=\"syn-error\" ...\n19.154  rustc            1046637 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name winnow --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winnow-0.7.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --allow=clippy::wildcard_imports --warn=clippy::verbose_file_reads --warn=unused_macro_rules --warn=unused_lifetimes ...\n19.161  rustc            1046640 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name time_macros --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/time-macros-0.2.19/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --warn=unused --warn=clippy::nursery --warn=clippy::all --warn=variant-size-differences ...\n19.178  rustc            1046649 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_shared --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_shared-0.11.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"std\", \"uncased\", \"unicase\")) ...\n19.184  rustc            1046659 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name deranged --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/deranged-0.3.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"powerfmt\" --cfg feature=\"std\" ...\n19.193  rustc            1046669 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_generator --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.11.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"criterion\")) -C metadata=e9cdae73507a9425 ...\n19.212  rustc            1046681 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unic_ucd_ident --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unic-ucd-ident-0.9.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"id\" --cfg feature=\"xid\" ...\n19.214  cc               1046686 1046617   0 /tmp/native-trace-1044207-1783999172017/shims/cc -m64 /target/debug/build/field-offset-453bc730e57f257a/rustcgl77u1/symbols.o /target/debug/build/field-offset-453bc730e57f257a/build_script_build-453bc730e57f257a.build_script_build.eac08306294b48bd-cgu.0. /target/debug/build/field-offset-453bc730e57f257a/build_script_build-453bc730e57f257a.9xqchss398o63wxpfbrsqoyb6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/librustc_version-f4b78ed04c511c58.rlib /target/debug/deps/libsemver-144842bd14407f6f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n19.218  cc               1046687 1046686   0 /usr/bin/cc -m64 /target/debug/build/field-offset-453bc730e57f257a/rustcgl77u1/symbols.o /target/debug/build/field-offset-453bc730e57f257a/build_script_build-453bc730e57f257a.build_script_build.eac08306294b48bd-cgu.0. /target/debug/build/field-offset-453bc730e57f257a/build_script_build-453bc730e57f257a.9xqchss398o63wxpfbrsqoyb6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/librustc_version-f4b78ed04c511c58.rlib /target/debug/deps/libsemver-144842bd14407f6f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n19.224  collect2         1046688 1046687   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRxUwTK.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.227  ld.lld           1046689 1046688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRxUwTK.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/field-offset-453bc730e57f257a/build_script_build-453bc730e57f257a ...\n19.230  rust-lld         1046689 1046688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRxUwTK.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.234  build-script-bu  1046693 1044862   0 /target/debug/build/semver-c618740620736b31/build-script-build\n19.238  rustc            1046695 1046693   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n19.243  cc               1046696 1046546   0 /tmp/native-trace-1044207-1783999172017/shims/cc -m64 /target/debug/build/thiserror-c8cdc86597298e7b/rustcJS24ZW/symbols.o /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.0.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.1.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.9ynru7dq8x5rowdfp4zmwji47.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.245  cc               1046697 1046696   0 /usr/bin/cc -m64 /target/debug/build/thiserror-c8cdc86597298e7b/rustcJS24ZW/symbols.o /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.0.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.1.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.9ynru7dq8x5rowdfp4zmwji47.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.249  collect2         1046698 1046697   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc240ky.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.251  ld.lld           1046699 1046698   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc240ky.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b ...\n19.253  rust-lld         1046699 1046698   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc240ky.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.266  rustc            1046718 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cookie-0.18.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"aes-gcm\", \"base64\", \"hkdf\", \"hmac\", \"key-expansion\", \"percent-encode\", \"percent-encoding\", \"private\", \"rand -C metadata=d1f02f79e30e5bd1 ...\n19.269  cc               1046719 1046567   0 /tmp/native-trace-1044207-1783999172017/shims/cc -m64 /target/debug/build/anyhow-aeb2c0a379103e54/rustcb2ibxR/symbols.o /target/debug/build/anyhow-aeb2c0a379103e54/build_script_build-aeb2c0a379103e54.build_script_build.817ee4ff42a8341e-cgu.0.rcgu.o /target/debug/build/anyhow-aeb2c0a379103e54/build_script_build-aeb2c0a379103e54.build_script_build.817ee4ff42a8341e-cgu.1.rcgu.o /target/debug/build/anyhow-aeb2c0a379103e54/build_script_build-aeb2c0a379103e54.auamdck3p4mz5lg9wf60b1ihe.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.271  cc               1046732 1046719   0 /usr/bin/cc -m64 /target/debug/build/anyhow-aeb2c0a379103e54/rustcb2ibxR/symbols.o /target/debug/build/anyhow-aeb2c0a379103e54/build_script_build-aeb2c0a379103e54.build_script_build.817ee4ff42a8341e-cgu.0.rcgu.o /target/debug/build/anyhow-aeb2c0a379103e54/build_script_build-aeb2c0a379103e54.build_script_build.817ee4ff42a8341e-cgu.1.rcgu.o /target/debug/build/anyhow-aeb2c0a379103e54/build_script_build-aeb2c0a379103e54.auamdck3p4mz5lg9wf60b1ihe.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.276  collect2         1046738 1046732   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRag4Oa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.279  ld.lld           1046739 1046738   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRag4Oa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/anyhow-aeb2c0a379103e54/build_script_build-aeb2c0a379103e54 ...\n19.281  rust-lld         1046739 1046738   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRag4Oa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.313  cc               1046766 1046718   0 /tmp/native-trace-1044207-1783999172017/shims/cc -m64 /target/debug/build/cookie-aaee0c33a9949f02/rustcVCrkL2/symbols.o /target/debug/build/cookie-aaee0c33a9949f02/build_script_build-aaee0c33a9949f02.build_script_build.62ebe6f9374b65a6-cgu.0.rcgu.o /target/debug/build/cookie-aaee0c33a9949f02/build_script_build-aaee0c33a9949f02.6v8z8tf26ll3puw917wisinib.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.315  cc               1046767 1046766   0 /usr/bin/cc -m64 /target/debug/build/cookie-aaee0c33a9949f02/rustcVCrkL2/symbols.o /target/debug/build/cookie-aaee0c33a9949f02/build_script_build-aaee0c33a9949f02.build_script_build.62ebe6f9374b65a6-cgu.0.rcgu.o /target/debug/build/cookie-aaee0c33a9949f02/build_script_build-aaee0c33a9949f02.6v8z8tf26ll3puw917wisinib.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.322  collect2         1046770 1046767   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHrWuWN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.324  ld.lld           1046771 1046770   0 \n19.329  rust-lld         1046771 1046770   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHrWuWN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/cookie-aaee0c33a9949f02/build_script_build-aaee0c33a9949f02 ... /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHrWuWN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.346  build-script-bu  1046777 1044862   0 /target/debug/build/field-offset-453bc730e57f257a/build-script-build\n19.350  rustc            1046778 1046777   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.362  build-script-bu  1046794 1044862   0 /target/debug/build/thiserror-c8cdc86597298e7b/build-script-build\n19.365  rustc            1046800 1046777   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.366  build-script-bu  1046799 1044862   0 /target/debug/build/anyhow-aeb2c0a379103e54/build-script-build\n19.367  rustc            1046801 1046794   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2018 --crate-name=thiserror --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/thiserror-04ce202668f2e8df/out/probe build/probe.rs --target powerpc64le-unknown-linux-gnu\n19.373  rustc            1046802 1046799   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2018 --crate-name=anyhow --crate-type=lib --emit=dep-info,metadata --cap-lints=allow --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/anyhow-39302f1b7a73d3d5/out/probe build/probe.rs --target powerpc64le-unknown-linux-gnu\n19.385  rustc            1046811 1046777   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.388  rustc            1046804 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_conv --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-conv-0.1.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unused --warn=unreachable-pub --deny=clippy::std-instead-of-core --warn=missing-docs --deny=clippy::alloc-instead-of-core --check-cfg ...\n19.405  rustc            1046820 1046794   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n19.411  rustc            1046821 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name field_offset --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/field-offset-0.3.6/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=34077b7d93a5ffb9 ...\n19.416  rustc            1046822 1046799   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n19.442  rustc            1046831 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bytes --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bytes-1.9.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n19.445  rustc            1046835 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name toml_writer --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_writer-1.0.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::wildcard_imports --warn=clippy::verbose_file_reads --warn=clippy::use_self --warn=unused_qualifications ...\n19.449  rustc            1046837 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name anyhow --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anyhow-1.0.95/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n19.452  rustc            1046838 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name time_core --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/time-core-0.1.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=45138d20d14d6601 ...\n19.477  rustc            1046855 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name semver --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/semver-1.0.24/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n19.483  build-script-bu  1046860 1044862   0 /target/debug/build/cookie-aaee0c33a9949f02/build-script-build\n19.489  rustc            1046864 1046860   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --verbose --version\n19.489  rustc            1046862 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"devtools\", \"macos-private-api\")) -C metadata=0a834e77f63c31ee ...\n19.503  rustc            1046870 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name log --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.22/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"kv\", \"kv_serde\", \"kv_std\", \"kv_sval\", \"kv_unstable\", \"kv_unstable_serde\", \"kv_unstable_std\", \"kv_unstable_s -C metadata=d7bf86fa365f1614 ...\n19.511  rustc            1046875 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name glob --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=99df842a04eb3802 ...\n19.519  rustc            1046881 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name dunce --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dunce-1.0.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=9455cf1f9371b24a ...\n19.530  rustc            1046885 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name raw_window_handle --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/raw-window-handle-0.6.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"std\", \"wasm-bindgen\", \"wasm-bindgen-0-2\")) -C metadata=d3d792437b2c7c94 ...\n19.593  cc               1046916 1046862   0 /tmp/native-trace-1044207-1783999172017/shims/cc -m64 /target/debug/build/tauri-runtime-041cb4f271a42860/rustc4kZYbK/symbols.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.1142o21yao9233spzvq2x04x0.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.1acozz5brdjul0vtt34mt28xf.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.1dbd33sl37kd4o8uhh3sp8939.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.2efy3ke9fiwntvupe0v8mp7j0.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.33xi0c99e13apvu82zvvoggmx.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.3dy38delsy331bsac3sa2nr5h.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.4ftt179efhe9eq42byz8ggehz.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.bcn0i1fkuwg81hlr99vc1lvr1.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.bmu6zotk1prfhinopmqbd27hx.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.c3ippwa376yaugsv7uo9r7rs2.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.cmft28nnc0mdbh1108s4mqbj6.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.d7vgi49qoj0duh1u512768ijc.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.efgr3oy0zezjits38be8aac2f.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.1aaytyhr7o2i47hx7atkjd930.16ie3yq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n19.595  cc               1046917 1046916   0 /usr/bin/cc -m64 /target/debug/build/tauri-runtime-041cb4f271a42860/rustc4kZYbK/symbols.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.1142o21yao9233spzvq2x04x0.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.1acozz5brdjul0vtt34mt28xf.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.1dbd33sl37kd4o8uhh3sp8939.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.2efy3ke9fiwntvupe0v8mp7j0.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.33xi0c99e13apvu82zvvoggmx.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.3dy38delsy331bsac3sa2nr5h.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.4ftt179efhe9eq42byz8ggehz.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.bcn0i1fkuwg81hlr99vc1lvr1.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.bmu6zotk1prfhinopmqbd27hx.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.c3ippwa376yaugsv7uo9r7rs2.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.cmft28nnc0mdbh1108s4mqbj6.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.d7vgi49qoj0duh1u512768ijc.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.efgr3oy0zezjits38be8aac2f.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.1aaytyhr7o2i47hx7atkjd930.16ie3yq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n19.599  collect2         1046920 1046917   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccEua0q9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.601  ld.lld           1046921 1046920   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccEua0q9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860 ...\n19.603  rust-lld         1046921 1046920   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccEua0q9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.700  build-script-bu  1046954 1044862   0 /target/debug/build/tauri-runtime-041cb4f271a42860/build-script-build\n19.882  rustc            1046987 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name http --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/http-1.3.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n20.067  cc               1047008 1046640   0 /tmp/native-trace-1044207-1783999172017/shims/cc -Wl,--version-script=/target/debug/deps/rustc05Elx9/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc05Elx9/symbols.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.00.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.01.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.02.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.03.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.04.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.05.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.06.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.07.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.08.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.09.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.10.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.11.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.12.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.13.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.14.rcgu.o ...\n20.068  cc               1047009 1047008   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc05Elx9/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc05Elx9/symbols.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.00.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.01.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.02.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.03.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.04.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.05.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.06.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.07.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.08.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.09.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.10.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.11.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.12.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.13.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.14.rcgu.o ...\n20.071  collect2         1047010 1047009   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLXq9H5.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libtime_macros-ba1d33f7f7b7ef9e.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc05Elx9/raw-dylibs ...\n20.072  ld.lld           1047011 1047010   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLXq9H5.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libtime_macros-ba1d33f7f7b7ef9e.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc05Elx9/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n20.073  rust-lld         1047011 1047010   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLXq9H5.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libtime_macros-ba1d33f7f7b7ef9e.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n20.113  rustc            1047033 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name toml_datetime --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_datetime-0.6.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::wildcard_imports --warn=clippy::verbose_file_reads --warn=unused_qualifications --warn=unused_macro_rules ...\n20.115  rustc            1047034 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde_spanned --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_spanned-0.6.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::wildcard_imports --warn=clippy::verbose_file_reads --warn=unused_qualifications --warn=unused_macro_rules ...\n20.154  rustc            1047043 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name time --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/time-0.3.37/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unused --warn=clippy::nursery --warn=clippy::all --warn=variant-size-differences --warn=clippy::use-debug --warn=clippy::unwrap-used ...\n20.208  rustc            1047055 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name toml_edit --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_edit-0.20.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"perf\", \"serde\", \"unbounded\")) ...\n20.211  rustc            1047056 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name toml_edit --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_edit-0.22.24/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::wildcard_imports --warn=clippy::verbose_file_reads --warn=unused_qualifications --warn=unused_macro_rules ...\n20.213  rustc            1047057 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name toml_edit --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_edit-0.19.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"perf\", \"serde\", \"unbounded\")) ...\n20.490  rustc            1047082 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_automata --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"dfa-onepass\" --cfg feature=\"hybrid\" ...\n20.526  rustc            1047089 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name toml_parser --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_parser-1.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::wildcard_imports --warn=clippy::verbose_file_reads --warn=clippy::use_self --warn=unused_qualifications ...\n21.160  runc             1047119 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process812093832 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n21.166  exe              1047131 1047119   0 /proc/self/exe init\n21.169  rustc            1047129 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cookie --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cookie-0.18.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"aes-gcm\", \"base64\", \"hkdf\", \"hmac\", \"key-expansion\", \"percent-encode\", \"percent-encoding\", \"private\", \"rand -C metadata=c7a9e4cc936ec7a4 ...\n21.191  curl             1047133 1047119   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n21.292  rustc            1047154 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name synstructure --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/synstructure-0.13.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n21.294  rustc            1047155 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name darling_core --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/darling_core-0.20.10/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"strsim\" --cfg feature=\"suggestions\" --check-cfg cfg(docsrs,test) ...\n21.354  rustc            1047168 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_crate --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-crate-2.0.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=c2daddb314f90f65 ...\n21.508  rustc            1047188 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_crate --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-crate-1.3.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=de23b41fddf46269 ...\n21.571  runc             1047201 1035510   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e94d34a6c413ce287ac263ed4bbb92fd713a2fb1fc661897f49865b438d --log-format json --systemd-cgroup kill --all e94d34a6c413ce287ac263ed4bbb92fd713a2fb1fc661897f49865b438d72c6f 9\n21.595  runc             1047207 1035510   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e94d34a6c413ce287ac263ed4bbb92fd713a2fb1fc661897f49865b438d --log-format json --systemd-cgroup delete e94d34a6c413ce287ac263ed4bbb92fd713a2fb1fc661897f49865b438d72c6f\n21.648  rustc            1047221 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name toml --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml-0.8.20/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::wildcard_imports --warn=clippy::verbose_file_reads --warn=unused_qualifications --warn=unused_macro_rules ...\n21.831  containerd-shim  1047251 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id e94d34a6c413ce287ac263ed4bbb92fd713a2fb1fc661897f49865b438d72c6f -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e94d34a6c413ce287ac263ed4bbb92fd713a2fb1fc661897f49865b438d delete\n21.837  runc             1047258 1047251   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e94d34a6c413ce287ac263ed4bbb92fd713a2fb1fc661897f49865b438d72c6 --log-format json delete --force e94d34a6c413ce287ac263ed4bbb92fd713a2fb1fc661897f49865b438d72c6f\n"
}
```

#### Record 28

```json
{
  "argv": [
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039208,
  "build_script_target_dir": "tree-sitter-language-04f523abf8aa8aa2",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build",
  "pid": 1039208,
  "ppid": 1039017,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-language",
    "version": "0.1.7",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/out"
}
```

#### Record 29

```json
{
  "argv": [
    "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039962,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build-script-build",
  "pid": 1039962,
  "ppid": 1039017,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out"
}
```

#### Record 30

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-E",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/3936375916911810436detect_compiler_famil"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039962,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 1039963,
  "ppid": 1039962,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 31

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-E",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/3936375916911810436detect_compiler_famil",
    "-msecure-plt",
    "-mcpu=power8",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039962,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 1039964,
  "ppid": 1039963,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 32

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039962,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 1039965,
  "ppid": 1039962,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 33

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-E",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/7686078308318996587detect_compiler_famil"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039962,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 1039966,
  "ppid": 1039962,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 34

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-E",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/7686078308318996587detect_compiler_famil",
    "-msecure-plt",
    "-mcpu=power8",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039962,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 1039968,
  "ppid": 1039966,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 35

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039962,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 1039970,
  "ppid": 1039962,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 36

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-m64",
    "-Wall",
    "-Wextra",
    "-Wno-unused-value",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/flag_check",
    "-c",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/flag_check.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039962,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 1039971,
  "ppid": 1039962,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 37

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/flag_check.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "flag_check.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/flag_check",
    "-O0",
    "-Wall",
    "-Wextra",
    "-Wno-unused-value",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039962,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 1039972,
  "ppid": 1039971,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 38

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/flag_check",
    "/tmp/cc2uOCSX.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039962,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 1039991,
  "ppid": 1039971,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_cwd_recovered_from_compiler_parent": true
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
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-std=c11",
    "-I",
    "src",
    "-Wall",
    "-Wextra",
    "-Wno-unused-value",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-parser.o",
    "-c",
    "src/parser.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039962,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 1039994,
  "ppid": 1039962,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "src",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "src/parser.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "parser.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-parser.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039962,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 1039997,
  "ppid": 1039994,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 41

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "src",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-parser.o",
    "/tmp/ccjIpBUD.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039962,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 1041162,
  "ppid": 1039994,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-std=c11",
    "-I",
    "src",
    "-Wall",
    "-Wextra",
    "-Wno-unused-value",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-scanner.o",
    "-c",
    "src/scanner.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039962,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 1041224,
  "ppid": 1039962,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
    "src",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "src/scanner.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "scanner.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-scanner.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039962,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 1041225,
  "ppid": 1041224,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 44

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "src",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-scanner.o",
    "/tmp/ccmyfBzH.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039962,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 1041255,
  "ppid": 1041224,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 45

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cqD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/libtree-sitter-ruby.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-parser.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-scanner.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039962,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 1041258,
  "ppid": 1039962,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 46

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "sD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/libtree-sitter-ruby.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1039962,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 1041261,
  "ppid": 1039962,
  "root_cargo_pid": 1039017,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 47

```json
{
  "crate": "tree-sitter-language",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "event_id": "bsrun:9216784ad2aeda3e:28bb85b0dc13bc9f:6e85cc7cb4cad71c",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "out_dir": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
  "success": true,
  "target": null,
  "version": "0.1.7",
  "_owner": {
    "crate": "tree-sitter-language",
    "version": "0.1.7",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
    "source": "cwd_prefix"
  }
}
```

#### Record 48

```json
{
  "crate": "tree-sitter-ruby",
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "event_id": "bsrun:a7f70ca37af6a983:222d6a9edf7103b1:b37d15792eb1b0fe",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
  "success": true,
  "target": null,
  "version": "0.23.1",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  }
}
```

#### Record 49

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/flag_check.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "flag_check.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/flag_check",
    "-O0",
    "-Wall",
    "-Wextra",
    "-Wno-unused-value",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "..."
  ],
  "src": "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/flag_check.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/flag_check",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 1039972,
  "ppid": 1039971,
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "root_cargo_pid": 1039017,
  "build_script_root_pid": 1039962,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 50

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "src",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "src/parser.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "parser.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-parser.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "..."
  ],
  "src": "src/parser.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-parser.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 1039997,
  "ppid": 1039994,
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "root_cargo_pid": 1039017,
  "build_script_root_pid": 1039962,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 51

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "src",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "src/scanner.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "scanner.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-scanner.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "..."
  ],
  "src": "src/scanner.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-scanner.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 1041225,
  "ppid": 1041224,
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "root_cargo_pid": 1039017,
  "build_script_root_pid": 1039962,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 52

```json
{
  "event": "archive",
  "tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "real_tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cqD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/libtree-sitter-ruby.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-parser.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-scanner.o"
  ],
  "archive": "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/libtree-sitter-ruby.a",
  "objects": [
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-parser.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-scanner.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 1041258,
  "ppid": 1039962,
  "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "root_cargo_pid": 1039017,
  "build_script_root_pid": 1039962,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
  "_owner": {
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
    "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T03:19:47.342557+00:00",
  "crate": "tree-sitter-ruby",
  "version": "0.23.1",
  "architecture": "ppc64le",
  "duration_seconds": 34.382303731981665,
  "trace_record_count": 48,
  "trace_owner_summary": {
    "owner_package_count": 12,
    "owner_packages": [
      {
        "crate": "tree-sitter-language",
        "version": "0.1.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/Cargo.toml"
      },
      {
        "crate": "streaming-iterator",
        "version": "0.1.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#streaming-iterator@0.1.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/streaming-iterator-0.1.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/streaming-iterator-0.1.9/Cargo.toml"
      },
      {
        "crate": "find-msvc-tools",
        "version": "0.1.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml"
      },
      {
        "crate": "regex-automata",
        "version": "0.4.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/Cargo.toml"
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
        "crate": "tree-sitter",
        "version": "0.24.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter@0.24.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-0.24.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-0.24.7/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "2.8.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml"
      },
      {
        "crate": "regex",
        "version": "1.13.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.13.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0/Cargo.toml"
      },
      {
        "crate": "shlex",
        "version": "2.0.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml"
      },
      {
        "crate": "cc",
        "version": "1.2.67",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml"
      },
      {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
        "manifest_path": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1/Cargo.toml"
      }
    ],
    "attributed_event_count": 27,
    "unattributed_event_count": 21,
    "owners": [
      {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "event_count": 19,
        "kind_counts": {
          "native_trace_root_context": 1,
          "exec": 1,
          "used_input": 13,
          "link": 1,
          "exec_context": 1,
          "resolved_link": 1,
          "build_script_run": 1
        }
      },
      {
        "crate": "tree-sitter-language",
        "version": "0.1.7",
        "event_count": 8,
        "kind_counts": {
          "exec": 1,
          "used_input": 3,
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
      "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "workspace_root": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
          "name": "cc",
          "version": "1.2.67",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
          "name": "find-msvc-tools",
          "version": "0.1.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
          "name": "memchr",
          "version": "2.8.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
          "name": "shlex",
          "version": "2.0.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#streaming-iterator@0.1.9",
          "name": "streaming-iterator",
          "version": "0.1.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/streaming-iterator-0.1.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/streaming-iterator-0.1.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter@0.24.7",
          "name": "tree-sitter",
          "version": "0.24.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-0.24.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-0.24.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
          "name": "tree-sitter-language",
          "version": "0.1.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7"
        },
        {
          "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
          "name": "tree-sitter-ruby",
          "version": "0.23.1",
          "manifest_path": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1"
        }
      ],
      "_owner": {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/symbols.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "exit_code": 0,
      "kind": "exec",
      "pid": 1039115,
      "ppid": 1039045,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-language",
        "version": "0.1.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/symbols.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-language",
      "cargo_pkg_version": "0.1.7",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "event_id": "used:cc:d9861ad91616b5cc:82817ea9f0745c96:085e3bf50b18abef",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
      "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/symbols.o",
      "pid": 1039115,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-language",
        "version": "0.1.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/symbols.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-language",
      "cargo_pkg_version": "0.1.7",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "event_id": "used:cc:d9861ad91616b5cc:04d242bb52149c08:085e3bf50b18abef",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
      "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
      "pid": 1039115,
      "sha256": "da99707d1d8127a1f25af4f3ba373e5e750453a5f3cf905bff78742f1d51481e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-language",
        "version": "0.1.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/symbols.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-language",
      "cargo_pkg_version": "0.1.7",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "event_id": "used:cc:d9861ad91616b5cc:22a29f0d0c58fcfa:085e3bf50b18abef",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
      "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
      "pid": 1039115,
      "sha256": "77ac94236c6fa2d2c7f071d002442abdff45a87fd63834eafb9403a64fea154d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-language",
        "version": "0.1.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/symbols.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/symbols.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/raw-dylibs",
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
      "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-language",
        "version": "0.1.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/symbols.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "cargo_pkg_name": "tree-sitter-language",
      "cargo_pkg_version": "0.1.7",
      "context_path": "/tmp/native-trace-1038682-1783999157895/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-1038682-1783999157895/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 1039115,
      "ppid": 1039045,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "_owner": {
        "crate": "tree-sitter-language",
        "version": "0.1.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/symbols.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2",
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
          "directory": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcKAgARC/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-1039115-1783999160316033243.map",
      "pid": 1039115,
      "ppid": 1039045,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-1039115-1783999160316033243.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "tree-sitter-language",
        "version": "0.1.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "exit_code": 0,
      "kind": "exec",
      "pid": 1039886,
      "ppid": 1039845,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-ruby",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "event_id": "used:cc:c07c8c8af6666626:a4931358f891e754:eb2d13ccf491a7e4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
      "pid": 1039886,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-ruby",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "event_id": "used:cc:c07c8c8af6666626:439a9f3debb82834:eb2d13ccf491a7e4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
      "pid": 1039886,
      "sha256": "7c2c8d7a9e88e9d920fe9bb35f5d8329bc2fa01b4b9a1f9f77609d93d833b37a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-ruby",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "event_id": "used:cc:c07c8c8af6666626:29204fff3d3f2419:eb2d13ccf491a7e4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
      "pid": 1039886,
      "sha256": "f75d4281c02642d0ad586179ee11c63f34983f342f1d754ddabeddcd932da3c2",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-ruby",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "event_id": "used:cc:c07c8c8af6666626:167f7a4dbe9dac96:eb2d13ccf491a7e4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
      "pid": 1039886,
      "sha256": "736297d8a4b342d74bdf07a1168f68aa0f588fb99b006524192070f0ce3c4c68",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-ruby",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "event_id": "used:cc:c07c8c8af6666626:309f4f7b75215560:eb2d13ccf491a7e4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
      "pid": 1039886,
      "sha256": "23b7ced54cfc2de5e097e1a75322e9e68a9f89dfe8c32351e552ab475cccb3be",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-ruby",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "event_id": "used:cc:c07c8c8af6666626:7ad2963acb00200d:eb2d13ccf491a7e4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
      "pid": 1039886,
      "sha256": "9ca1d2b9c72295ed5dece6525666f32cc8e1786a825f8691403e3f1fd5b7cdc4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-ruby",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "event_id": "used:cc:c07c8c8af6666626:e50029fc7f53dcc4:eb2d13ccf491a7e4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
      "pid": 1039886,
      "sha256": "c0985357418e67a5b05094601c0b8c5fdbaa79f26d2c52976084dfc0e9766c12",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-ruby",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "event_id": "used:cc:c07c8c8af6666626:a3c171880e82c55a:eb2d13ccf491a7e4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
      "pid": 1039886,
      "sha256": "1ceca619e7f7b7e56150caa61e6a38691ba9de60746bb9167432992da867b7b3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-ruby",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "event_id": "used:cc:c07c8c8af6666626:b50148b77213cc07:eb2d13ccf491a7e4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
      "pid": 1039886,
      "sha256": "0afd3eb636a678d855fb917cd187c3648b23dc4d1228f4d8e1efdf5d780a02f5",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-ruby",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "event_id": "used:cc:c07c8c8af6666626:9bb3af152572cbbd:eb2d13ccf491a7e4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
      "pid": 1039886,
      "sha256": "07a8e471ff1955076a857ebcd609163f95da42c38a86cb4d1e25e30775f5b9d5",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-ruby",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "event_id": "used:cc:c07c8c8af6666626:efc3111a30b0d4d8:eb2d13ccf491a7e4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
      "pid": 1039886,
      "sha256": "aab7dba120c228dbfbfdb47a9560edca62c518058f879c27e7b3c3f2e8f34f76",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-ruby",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "event_id": "used:cc:c07c8c8af6666626:4608b7f6b260db60:eb2d13ccf491a7e4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
      "pid": 1039886,
      "sha256": "5e3ca6c3f1ba4cdaec1cab961ee9b7c15a37432d6b1146dccd953695a3fb38a1",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-ruby",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "event_id": "used:cc:c07c8c8af6666626:b61fb8385f86f263:eb2d13ccf491a7e4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
      "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
      "pid": 1039886,
      "sha256": "8e9fcdfe4a5e81837f4ccd860ef68675202667939414402059f7a36efa8afcbf",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
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
      "output": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "cargo_pkg_name": "tree-sitter-ruby",
      "cargo_pkg_version": "0.23.1",
      "context_path": "/tmp/native-trace-1038682-1783999157895/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-1038682-1783999157895/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 1039886,
      "ppid": 1039845,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "_owner": {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC",
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
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
          "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/rustcRVJxVC/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1nnt23i5k2foxiiqc4yen7go3.1c8dafb.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.1qt531ascieofysiuzd6879dt.1c8dafb.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.34tbbl746o31x70qc4x0ma65y.1c8dafb.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.354xu7urfq4o532jjdhbt4w1d.1c8dafb.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.381hri81s151nhnlk9ju5j6w6.1c8dafb.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.3n281hctca8rq9glopqht3ij3.1c8dafb.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.7zj3igw25hw1vwj3z2dr5hiwf.1c8dafb.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9395qy1b8znfujc3l9qye2dva.1c8dafb.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9cyj9q6pgiovj8usxpuodhgtc.1c8dafb.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.d3ed6osps8ipcyr9mtk3ekb74.1c8dafb.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.el8l3q0vf0cq1y7shrh22rr09.1c8dafb.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build_script_build-1ee4b1adcc2eb995.9c967hfb3hh9qerae95iuqy1u.1c8dafb.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-1039886-1783999161964209769.map",
      "pid": 1039886,
      "ppid": 1039845,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-1039886-1783999161964209769.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
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
      "parsed_event_count": 1315,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1316,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "r- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n18.981  collect2         1046557 1046552   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccrb954z.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libproc_macro_error_attr-c0f372eb48247273.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcvuYn6R/raw-dylibs ...\n18.986  ld.lld           1046561 1046557   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccrb954z.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr-c0f372eb48247273.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcvuYn6R/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.990  rust-lld         1046561 1046557   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccrb954z.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr-c0f372eb48247273.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n18.998  cc               1046562 1046508   0 /tmp/native-trace-1044207-1783999172017/shims/cc -m64 /target/debug/build/gtk-c9fea2000bcdf02d/rustcIuaB6N/symbols.o /target/debug/build/gtk-c9fea2000bcdf02d/build_script_build-c9fea2000bcdf02d.build_script_build.96c7cbeb8cc76ef-cgu.0.rcgu.o /target/debug/build/gtk-c9fea2000bcdf02d/build_script_build-c9fea2000bcdf02d.94w0fhu215livx365ryijbq3u.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libpkg_config-60dc64799e6cfcae.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.001  cc               1046566 1046562   0 /usr/bin/cc -m64 /target/debug/build/gtk-c9fea2000bcdf02d/rustcIuaB6N/symbols.o /target/debug/build/gtk-c9fea2000bcdf02d/build_script_build-c9fea2000bcdf02d.build_script_build.96c7cbeb8cc76ef-cgu.0.rcgu.o /target/debug/build/gtk-c9fea2000bcdf02d/build_script_build-c9fea2000bcdf02d.94w0fhu215livx365ryijbq3u.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libpkg_config-60dc64799e6cfcae.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.007  collect2         1046568 1046566   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRIxxKA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.014  rustc            1046567 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anyhow-1.0.95/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n19.022  ld.lld           1046570 1046568   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRIxxKA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gtk-c9fea2000bcdf02d/build_script_build-c9fea2000bcdf02d ...\n19.025  rust-lld         1046570 1046568   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRIxxKA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.042  rustc            1046590 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_conv --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-conv-0.1.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unused --warn=unreachable-pub --deny=clippy::std-instead-of-core --warn=missing-docs --deny=clippy::alloc-instead-of-core --check-cfg ...\n19.108  rustc            1046617 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/field-offset-0.3.6/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=927ca445b27343e0 ...\n19.139  rustc            1046631 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bitflags --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"default\", \"example_generated\", \"rustc-dep-of-std\")) ...\n19.143  rustc            1046634 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-error-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"syn\" --cfg feature=\"syn-error\" ...\n19.154  rustc            1046637 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name winnow --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winnow-0.7.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --allow=clippy::wildcard_imports --warn=clippy::verbose_file_reads --warn=unused_macro_rules --warn=unused_lifetimes ...\n19.161  rustc            1046640 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name time_macros --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/time-macros-0.2.19/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --warn=unused --warn=clippy::nursery --warn=clippy::all --warn=variant-size-differences ...\n19.178  rustc            1046649 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_shared --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_shared-0.11.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"std\", \"uncased\", \"unicase\")) ...\n19.184  rustc            1046659 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name deranged --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/deranged-0.3.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"powerfmt\" --cfg feature=\"std\" ...\n19.193  rustc            1046669 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name phf_generator --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.11.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"criterion\")) -C metadata=e9cdae73507a9425 ...\n19.212  rustc            1046681 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unic_ucd_ident --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unic-ucd-ident-0.9.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"id\" --cfg feature=\"xid\" ...\n19.214  cc               1046686 1046617   0 /tmp/native-trace-1044207-1783999172017/shims/cc -m64 /target/debug/build/field-offset-453bc730e57f257a/rustcgl77u1/symbols.o /target/debug/build/field-offset-453bc730e57f257a/build_script_build-453bc730e57f257a.build_script_build.eac08306294b48bd-cgu.0. /target/debug/build/field-offset-453bc730e57f257a/build_script_build-453bc730e57f257a.9xqchss398o63wxpfbrsqoyb6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/librustc_version-f4b78ed04c511c58.rlib /target/debug/deps/libsemver-144842bd14407f6f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n19.218  cc               1046687 1046686   0 /usr/bin/cc -m64 /target/debug/build/field-offset-453bc730e57f257a/rustcgl77u1/symbols.o /target/debug/build/field-offset-453bc730e57f257a/build_script_build-453bc730e57f257a.build_script_build.eac08306294b48bd-cgu.0. /target/debug/build/field-offset-453bc730e57f257a/build_script_build-453bc730e57f257a.9xqchss398o63wxpfbrsqoyb6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/librustc_version-f4b78ed04c511c58.rlib /target/debug/deps/libsemver-144842bd14407f6f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n19.224  collect2         1046688 1046687   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRxUwTK.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.227  ld.lld           1046689 1046688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRxUwTK.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/field-offset-453bc730e57f257a/build_script_build-453bc730e57f257a ...\n19.230  rust-lld         1046689 1046688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRxUwTK.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.234  build-script-bu  1046693 1044862   0 /target/debug/build/semver-c618740620736b31/build-script-build\n19.238  rustc            1046695 1046693   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n19.243  cc               1046696 1046546   0 /tmp/native-trace-1044207-1783999172017/shims/cc -m64 /target/debug/build/thiserror-c8cdc86597298e7b/rustcJS24ZW/symbols.o /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.0.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.1.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.9ynru7dq8x5rowdfp4zmwji47.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.245  cc               1046697 1046696   0 /usr/bin/cc -m64 /target/debug/build/thiserror-c8cdc86597298e7b/rustcJS24ZW/symbols.o /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.0.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.1.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.9ynru7dq8x5rowdfp4zmwji47.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.249  collect2         1046698 1046697   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc240ky.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.251  ld.lld           1046699 1046698   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc240ky.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b ...\n19.253  rust-lld         1046699 1046698   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc240ky.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.266  rustc            1046718 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cookie-0.18.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"aes-gcm\", \"base64\", \"hkdf\", \"hmac\", \"key-expansion\", \"percent-encode\", \"percent-encoding\", \"private\", \"rand -C metadata=d1f02f79e30e5bd1 ...\n19.269  cc               1046719 1046567   0 /tmp/native-trace-1044207-1783999172017/shims/cc -m64 /target/debug/build/anyhow-aeb2c0a379103e54/rustcb2ibxR/symbols.o /target/debug/build/anyhow-aeb2c0a379103e54/build_script_build-aeb2c0a379103e54.build_script_build.817ee4ff42a8341e-cgu.0.rcgu.o /target/debug/build/anyhow-aeb2c0a379103e54/build_script_build-aeb2c0a379103e54.build_script_build.817ee4ff42a8341e-cgu.1.rcgu.o /target/debug/build/anyhow-aeb2c0a379103e54/build_script_build-aeb2c0a379103e54.auamdck3p4mz5lg9wf60b1ihe.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.271  cc               1046732 1046719   0 /usr/bin/cc -m64 /target/debug/build/anyhow-aeb2c0a379103e54/rustcb2ibxR/symbols.o /target/debug/build/anyhow-aeb2c0a379103e54/build_script_build-aeb2c0a379103e54.build_script_build.817ee4ff42a8341e-cgu.0.rcgu.o /target/debug/build/anyhow-aeb2c0a379103e54/build_script_build-aeb2c0a379103e54.build_script_build.817ee4ff42a8341e-cgu.1.rcgu.o /target/debug/build/anyhow-aeb2c0a379103e54/build_script_build-aeb2c0a379103e54.auamdck3p4mz5lg9wf60b1ihe.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.276  collect2         1046738 1046732   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRag4Oa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.279  ld.lld           1046739 1046738   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRag4Oa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/anyhow-aeb2c0a379103e54/build_script_build-aeb2c0a379103e54 ...\n19.281  rust-lld         1046739 1046738   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRag4Oa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.313  cc               1046766 1046718   0 /tmp/native-trace-1044207-1783999172017/shims/cc -m64 /target/debug/build/cookie-aaee0c33a9949f02/rustcVCrkL2/symbols.o /target/debug/build/cookie-aaee0c33a9949f02/build_script_build-aaee0c33a9949f02.build_script_build.62ebe6f9374b65a6-cgu.0.rcgu.o /target/debug/build/cookie-aaee0c33a9949f02/build_script_build-aaee0c33a9949f02.6v8z8tf26ll3puw917wisinib.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.315  cc               1046767 1046766   0 /usr/bin/cc -m64 /target/debug/build/cookie-aaee0c33a9949f02/rustcVCrkL2/symbols.o /target/debug/build/cookie-aaee0c33a9949f02/build_script_build-aaee0c33a9949f02.build_script_build.62ebe6f9374b65a6-cgu.0.rcgu.o /target/debug/build/cookie-aaee0c33a9949f02/build_script_build-aaee0c33a9949f02.6v8z8tf26ll3puw917wisinib.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.322  collect2         1046770 1046767   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHrWuWN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.324  ld.lld           1046771 1046770   0 \n19.329  rust-lld         1046771 1046770   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHrWuWN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/cookie-aaee0c33a9949f02/build_script_build-aaee0c33a9949f02 ... /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHrWuWN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.346  build-script-bu  1046777 1044862   0 /target/debug/build/field-offset-453bc730e57f257a/build-script-build\n19.350  rustc            1046778 1046777   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.362  build-script-bu  1046794 1044862   0 /target/debug/build/thiserror-c8cdc86597298e7b/build-script-build\n19.365  rustc            1046800 1046777   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.366  build-script-bu  1046799 1044862   0 /target/debug/build/anyhow-aeb2c0a379103e54/build-script-build\n19.367  rustc            1046801 1046794   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2018 --crate-name=thiserror --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/thiserror-04ce202668f2e8df/out/probe build/probe.rs --target powerpc64le-unknown-linux-gnu\n19.373  rustc            1046802 1046799   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2018 --crate-name=anyhow --crate-type=lib --emit=dep-info,metadata --cap-lints=allow --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/anyhow-39302f1b7a73d3d5/out/probe build/probe.rs --target powerpc64le-unknown-linux-gnu\n19.385  rustc            1046811 1046777   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.388  rustc            1046804 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_conv --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-conv-0.1.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unused --warn=unreachable-pub --deny=clippy::std-instead-of-core --warn=missing-docs --deny=clippy::alloc-instead-of-core --check-cfg ...\n19.405  rustc            1046820 1046794   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n19.411  rustc            1046821 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name field_offset --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/field-offset-0.3.6/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=34077b7d93a5ffb9 ...\n19.416  rustc            1046822 1046799   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n19.442  rustc            1046831 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bytes --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bytes-1.9.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n19.445  rustc            1046835 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name toml_writer --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_writer-1.0.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::wildcard_imports --warn=clippy::verbose_file_reads --warn=clippy::use_self --warn=unused_qualifications ...\n19.449  rustc            1046837 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name anyhow --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anyhow-1.0.95/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n19.452  rustc            1046838 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name time_core --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/time-core-0.1.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=45138d20d14d6601 ...\n19.477  rustc            1046855 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name semver --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/semver-1.0.24/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n19.483  build-script-bu  1046860 1044862   0 /target/debug/build/cookie-aaee0c33a9949f02/build-script-build\n19.489  rustc            1046864 1046860   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --verbose --version\n19.489  rustc            1046862 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"devtools\", \"macos-private-api\")) -C metadata=0a834e77f63c31ee ...\n19.503  rustc            1046870 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name log --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.22/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"kv\", \"kv_serde\", \"kv_std\", \"kv_sval\", \"kv_unstable\", \"kv_unstable_serde\", \"kv_unstable_std\", \"kv_unstable_s -C metadata=d7bf86fa365f1614 ...\n19.511  rustc            1046875 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name glob --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=99df842a04eb3802 ...\n19.519  rustc            1046881 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name dunce --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dunce-1.0.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=9455cf1f9371b24a ...\n19.530  rustc            1046885 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name raw_window_handle --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/raw-window-handle-0.6.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"std\", \"wasm-bindgen\", \"wasm-bindgen-0-2\")) -C metadata=d3d792437b2c7c94 ...\n19.593  cc               1046916 1046862   0 /tmp/native-trace-1044207-1783999172017/shims/cc -m64 /target/debug/build/tauri-runtime-041cb4f271a42860/rustc4kZYbK/symbols.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.1142o21yao9233spzvq2x04x0.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.1acozz5brdjul0vtt34mt28xf.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.1dbd33sl37kd4o8uhh3sp8939.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.2efy3ke9fiwntvupe0v8mp7j0.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.33xi0c99e13apvu82zvvoggmx.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.3dy38delsy331bsac3sa2nr5h.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.4ftt179efhe9eq42byz8ggehz.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.bcn0i1fkuwg81hlr99vc1lvr1.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.bmu6zotk1prfhinopmqbd27hx.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.c3ippwa376yaugsv7uo9r7rs2.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.cmft28nnc0mdbh1108s4mqbj6.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.d7vgi49qoj0duh1u512768ijc.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.efgr3oy0zezjits38be8aac2f.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.1aaytyhr7o2i47hx7atkjd930.16ie3yq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n19.595  cc               1046917 1046916   0 /usr/bin/cc -m64 /target/debug/build/tauri-runtime-041cb4f271a42860/rustc4kZYbK/symbols.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.1142o21yao9233spzvq2x04x0.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.1acozz5brdjul0vtt34mt28xf.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.1dbd33sl37kd4o8uhh3sp8939.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.2efy3ke9fiwntvupe0v8mp7j0.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.33xi0c99e13apvu82zvvoggmx.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.3dy38delsy331bsac3sa2nr5h.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.4ftt179efhe9eq42byz8ggehz.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.bcn0i1fkuwg81hlr99vc1lvr1.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.bmu6zotk1prfhinopmqbd27hx.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.c3ippwa376yaugsv7uo9r7rs2.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.cmft28nnc0mdbh1108s4mqbj6.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.d7vgi49qoj0duh1u512768ijc.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.efgr3oy0zezjits38be8aac2f.16ie3yq.rcgu.o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860.1aaytyhr7o2i47hx7atkjd930.16ie3yq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n19.599  collect2         1046920 1046917   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccEua0q9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.601  ld.lld           1046921 1046920   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccEua0q9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tauri-runtime-041cb4f271a42860/build_script_build-041cb4f271a42860 ...\n19.603  rust-lld         1046921 1046920   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccEua0q9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.700  build-script-bu  1046954 1044862   0 /target/debug/build/tauri-runtime-041cb4f271a42860/build-script-build\n19.882  rustc            1046987 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name http --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/http-1.3.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n20.067  cc               1047008 1046640   0 /tmp/native-trace-1044207-1783999172017/shims/cc -Wl,--version-script=/target/debug/deps/rustc05Elx9/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc05Elx9/symbols.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.00.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.01.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.02.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.03.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.04.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.05.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.06.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.07.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.08.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.09.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.10.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.11.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.12.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.13.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.14.rcgu.o ...\n20.068  cc               1047009 1047008   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc05Elx9/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc05Elx9/symbols.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.00.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.01.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.02.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.03.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.04.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.05.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.06.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.07.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.08.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.09.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.10.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.11.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.12.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.13.rcgu.o /target/debug/deps/time_macros-ba1d33f7f7b7ef9e.time_macros.9bbbb741c3e84376-cgu.14.rcgu.o ...\n20.071  collect2         1047010 1047009   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLXq9H5.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libtime_macros-ba1d33f7f7b7ef9e.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc05Elx9/raw-dylibs ...\n20.072  ld.lld           1047011 1047010   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLXq9H5.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libtime_macros-ba1d33f7f7b7ef9e.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc05Elx9/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n20.073  rust-lld         1047011 1047010   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLXq9H5.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libtime_macros-ba1d33f7f7b7ef9e.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n20.113  rustc            1047033 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name toml_datetime --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_datetime-0.6.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::wildcard_imports --warn=clippy::verbose_file_reads --warn=unused_qualifications --warn=unused_macro_rules ...\n20.115  rustc            1047034 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde_spanned --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_spanned-0.6.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::wildcard_imports --warn=clippy::verbose_file_reads --warn=unused_qualifications --warn=unused_macro_rules ...\n20.154  rustc            1047043 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name time --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/time-0.3.37/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unused --warn=clippy::nursery --warn=clippy::all --warn=variant-size-differences --warn=clippy::use-debug --warn=clippy::unwrap-used ...\n20.208  rustc            1047055 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name toml_edit --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_edit-0.20.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"perf\", \"serde\", \"unbounded\")) ...\n20.211  rustc            1047056 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name toml_edit --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_edit-0.22.24/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::wildcard_imports --warn=clippy::verbose_file_reads --warn=unused_qualifications --warn=unused_macro_rules ...\n20.213  rustc            1047057 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name toml_edit --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_edit-0.19.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"perf\", \"serde\", \"unbounded\")) ...\n20.490  rustc            1047082 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_automata --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"dfa-onepass\" --cfg feature=\"hybrid\" ...\n20.526  rustc            1047089 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name toml_parser --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_parser-1.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::wildcard_imports --warn=clippy::verbose_file_reads --warn=clippy::use_self --warn=unused_qualifications ...\n21.160  runc             1047119 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process812093832 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n21.166  exe              1047131 1047119   0 /proc/self/exe init\n21.169  rustc            1047129 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cookie --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cookie-0.18.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"aes-gcm\", \"base64\", \"hkdf\", \"hmac\", \"key-expansion\", \"percent-encode\", \"percent-encoding\", \"private\", \"rand -C metadata=c7a9e4cc936ec7a4 ...\n21.191  curl             1047133 1047119   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n21.292  rustc            1047154 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name synstructure --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/synstructure-0.13.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n21.294  rustc            1047155 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name darling_core --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/darling_core-0.20.10/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"strsim\" --cfg feature=\"suggestions\" --check-cfg cfg(docsrs,test) ...\n21.354  rustc            1047168 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_crate --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-crate-2.0.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=c2daddb314f90f65 ...\n21.508  rustc            1047188 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_crate --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-crate-1.3.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=de23b41fddf46269 ...\n21.571  runc             1047201 1035510   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e94d34a6c413ce287ac263ed4bbb92fd713a2fb1fc661897f49865b438d --log-format json --systemd-cgroup kill --all e94d34a6c413ce287ac263ed4bbb92fd713a2fb1fc661897f49865b438d72c6f 9\n21.595  runc             1047207 1035510   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e94d34a6c413ce287ac263ed4bbb92fd713a2fb1fc661897f49865b438d --log-format json --systemd-cgroup delete e94d34a6c413ce287ac263ed4bbb92fd713a2fb1fc661897f49865b438d72c6f\n21.648  rustc            1047221 1044862   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name toml --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml-0.8.20/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::wildcard_imports --warn=clippy::verbose_file_reads --warn=unused_qualifications --warn=unused_macro_rules ...\n21.831  containerd-shim  1047251 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id e94d34a6c413ce287ac263ed4bbb92fd713a2fb1fc661897f49865b438d72c6f -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e94d34a6c413ce287ac263ed4bbb92fd713a2fb1fc661897f49865b438d delete\n21.837  runc             1047258 1047251   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e94d34a6c413ce287ac263ed4bbb92fd713a2fb1fc661897f49865b438d72c6 --log-format json delete --force e94d34a6c413ce287ac263ed4bbb92fd713a2fb1fc661897f49865b438d72c6f\n"
    },
    {
      "argv": [
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1039208,
      "build_script_target_dir": "tree-sitter-language-04f523abf8aa8aa2",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build",
      "pid": 1039208,
      "ppid": 1039017,
      "root_cargo_pid": 1039017,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1039962,
      "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build-script-build",
      "pid": 1039962,
      "ppid": 1039017,
      "root_cargo_pid": 1039017,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-E",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/3936375916911810436detect_compiler_famil"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1039962,
      "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 1039963,
      "ppid": 1039962,
      "root_cargo_pid": 1039017,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-E",
        "-quiet",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/3936375916911810436detect_compiler_famil",
        "-msecure-plt",
        "-mcpu=power8",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1039962,
      "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 1039964,
      "ppid": 1039963,
      "root_cargo_pid": 1039017,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1039962,
      "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 1039965,
      "ppid": 1039962,
      "root_cargo_pid": 1039017,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-E",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/7686078308318996587detect_compiler_famil"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1039962,
      "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 1039966,
      "ppid": 1039962,
      "root_cargo_pid": 1039017,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-E",
        "-quiet",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/7686078308318996587detect_compiler_famil",
        "-msecure-plt",
        "-mcpu=power8",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1039962,
      "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 1039968,
      "ppid": 1039966,
      "root_cargo_pid": 1039017,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1039962,
      "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 1039970,
      "ppid": 1039962,
      "root_cargo_pid": 1039017,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-m64",
        "-Wall",
        "-Wextra",
        "-Wno-unused-value",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/flag_check",
        "-c",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/flag_check.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1039962,
      "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 1039971,
      "ppid": 1039962,
      "root_cargo_pid": 1039017,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/flag_check.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "flag_check.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/flag_check",
        "-O0",
        "-Wall",
        "-Wextra",
        "-Wno-unused-value",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 1039962,
      "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 1039972,
      "ppid": 1039971,
      "root_cargo_pid": 1039017,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/flag_check",
        "/tmp/cc2uOCSX.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1039962,
      "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 1039991,
      "ppid": 1039971,
      "root_cargo_pid": 1039017,
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
        "-std=c11",
        "-I",
        "src",
        "-Wall",
        "-Wextra",
        "-Wno-unused-value",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-parser.o",
        "-c",
        "src/parser.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1039962,
      "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 1039994,
      "ppid": 1039962,
      "root_cargo_pid": 1039017,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "src",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "src/parser.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "parser.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-parser.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-Wall",
        "-Wextra",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 1039962,
      "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 1039997,
      "ppid": 1039994,
      "root_cargo_pid": 1039017,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "src",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-parser.o",
        "/tmp/ccjIpBUD.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1039962,
      "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 1041162,
      "ppid": 1039994,
      "root_cargo_pid": 1039017,
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
        "-std=c11",
        "-I",
        "src",
        "-Wall",
        "-Wextra",
        "-Wno-unused-value",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-scanner.o",
        "-c",
        "src/scanner.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1039962,
      "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 1041224,
      "ppid": 1039962,
      "root_cargo_pid": 1039017,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "src",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "src/scanner.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "scanner.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-scanner.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-Wall",
        "-Wextra",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 1039962,
      "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 1041225,
      "ppid": 1041224,
      "root_cargo_pid": 1039017,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "src",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-scanner.o",
        "/tmp/ccmyfBzH.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1039962,
      "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 1041255,
      "ppid": 1041224,
      "root_cargo_pid": 1039017,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "cqD",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/libtree-sitter-ruby.a",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-parser.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/ea708c7824d36062-scanner.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1039962,
      "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 1041258,
      "ppid": 1039962,
      "root_cargo_pid": 1039017,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "sD",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-ruby-66fb1fc756cbec06/out/libtree-sitter-ruby.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1039962,
      "build_script_target_dir": "tree-sitter-ruby-1ee4b1adcc2eb995",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 1041261,
      "ppid": 1039962,
      "root_cargo_pid": 1039017,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "tree-sitter-language",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "event_id": "bsrun:9216784ad2aeda3e:28bb85b0dc13bc9f:6e85cc7cb4cad71c",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "out_dir": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
      "success": true,
      "target": null,
      "version": "0.1.7",
      "_owner": {
        "crate": "tree-sitter-language",
        "version": "0.1.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "tree-sitter-ruby",
      "cwd": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "event_id": "bsrun:a7f70ca37af6a983:222d6a9edf7103b1:b37d15792eb1b0fe",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
      "out_dir": "/target/debug/build/tree-sitter-ruby-1ee4b1adcc2eb995/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
      "success": true,
      "target": null,
      "version": "0.23.1",
      "_owner": {
        "crate": "tree-sitter-ruby",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1#tree-sitter-ruby@0.23.1",
        "manifest_dir": "/tmp/crate-build-ppc64le-5qug_kne/src/tree-sitter-ruby-0.23.1",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
  "item": {
    "rank": 4057,
    "crate": "tree-sitter-ruby",
    "version": "0.23.1",
    "crate_id": "306055",
    "version_id": "1335326",
    "downloads": 2059723,
    "cumulative_downloads": 109856097690,
    "cumulative_share_of_global": 0.41072658834392634,
    "status": "ok",
    "has_build_script": true,
    "build_script_path": "bindings/rust/build.rs",
    "build_script_exists": true,
    "package_build_field": "bindings/rust/build.rs",
    "build_script_reason": "package_build_path",
    "download_source": "local"
  }
}
```
