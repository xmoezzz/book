# `tree-sitter-c-sharp` `0.23.1`

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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
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
  "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
    "/target/debug/deps",
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
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-1063497-1783999245480160619.map",
  "pid": 1063497,
  "ppid": 1063480,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1063497-1783999245480160619.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/libtree-sitter-c-sharp.a`

Owner: `tree-sitter-c-sharp` `0.23.1`

### Source files

* `/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1/src/parser.c`
* `/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1/src/scanner.c`

### Source acquisition records

_None._

### Source preparation records

#### Record 1

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-std=c11",
    "-I",
    "src",
    "-Wall",
    "-Wextra",
    "-Wno-unused-value",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-parser.o",
    "-c",
    "src/parser.c",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063518,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 1063528,
  "ppid": 1063518,
  "root_cargo_pid": 1063357,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 2

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-std=c11",
    "-I",
    "src",
    "-Wall",
    "-Wextra",
    "-Wno-unused-value",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-scanner.o",
    "-c",
    "src/scanner.c",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063518,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 1064068,
  "ppid": 1063518,
  "root_cargo_pid": 1063357,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_cwd_recovered_from_build_script_run": true
}
```

### Compilation records

#### Record 1

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "src",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "src/scanner.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/",
    "-dumpbase",
    "ea708c7824d36062-scanner.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "src/scanner.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-scanner.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 1064069,
  "ppid": 1064068,
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "root_cargo_pid": 1063357,
  "build_script_root_pid": 1063518,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 2

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "src",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "src/parser.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/",
    "-dumpbase",
    "ea708c7824d36062-parser.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "src/parser.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-parser.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 1063529,
  "ppid": 1063528,
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "root_cargo_pid": 1063357,
  "build_script_root_pid": 1063518,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

### Archive records

#### Record 1

```json
{
  "event": "archive",
  "tool": "/usr/bin/riscv64-linux-gnu-ar",
  "real_tool": "/usr/bin/riscv64-linux-gnu-ar",
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "cqD",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/libtree-sitter-c-sharp.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-parser.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-scanner.o"
  ],
  "archive": "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/libtree-sitter-c-sharp.a",
  "objects": [
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-parser.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-scanner.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 1064071,
  "ppid": 1063518,
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "root_cargo_pid": 1063357,
  "build_script_root_pid": 1063518,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
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
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "workspace_root": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1"
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
      "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
      "name": "tree-sitter-c-sharp",
      "version": "0.23.1",
      "manifest_path": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
      "name": "tree-sitter-language",
      "version": "0.1.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7"
    }
  ],
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/raw-dylibs",
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
  "pid": 1063384,
  "ppid": 1063370,
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/raw-dylibs",
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
  "event_id": "used:cc:d9861ad91616b5cc:edfd328aa6753eb2:085e3bf50b18abef",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
  "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o",
  "pid": 1063384,
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/raw-dylibs",
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
  "pid": 1063384,
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/raw-dylibs",
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
  "pid": 1063384,
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/raw-dylibs",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/raw-dylibs",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/raw-dylibs",
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
  "context_path": "/tmp/native-trace-1062789-1783999241328/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-1062789-1783999241328/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 1063384,
  "ppid": 1063370,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/raw-dylibs",
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
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2",
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
      "directory": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o",
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
  "map_path": "/tmp/native-trace-link-cc-1063384-1783999244726377014.map",
  "pid": 1063384,
  "ppid": 1063370,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1063384-1783999244726377014.map"
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "exit_code": 0,
  "kind": "exec",
  "pid": 1063497,
  "ppid": 1063480,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c-sharp",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "event_id": "used:cc:f4ff3c72e2a5e3e5:43a23aa3f5603b47:7684f49140d540dc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
  "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
  "pid": 1063497,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c-sharp",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "event_id": "used:cc:f4ff3c72e2a5e3e5:1e7b026ec3865928:7684f49140d540dc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
  "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
  "pid": 1063497,
  "sha256": "f5ee8725de09ccf42aeba66c08cdd18121cd1dcdd39ff76d1fb485f89195fe0e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c-sharp",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "event_id": "used:cc:f4ff3c72e2a5e3e5:7a8eada1e9059940:7684f49140d540dc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
  "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
  "pid": 1063497,
  "sha256": "4a9e60b0dafa512317278b5221b41047d38f1b257caaa50c03a6b3008f5b7a1c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c-sharp",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "event_id": "used:cc:f4ff3c72e2a5e3e5:4d36d936a59ae38a:7684f49140d540dc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
  "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
  "pid": 1063497,
  "sha256": "55f8e13c92b124d990f5be26ef09dadc3a4409420bf448cd18739b42303a8e0e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c-sharp",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "event_id": "used:cc:f4ff3c72e2a5e3e5:c38bd32db620722a:7684f49140d540dc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
  "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
  "pid": 1063497,
  "sha256": "7d0dd79164003bd8fdbb94fb93727de8cf9a5612cebb8fc2a14b7e5b3cf71a27",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c-sharp",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "event_id": "used:cc:f4ff3c72e2a5e3e5:52e81273f2ea2cde:7684f49140d540dc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
  "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
  "pid": 1063497,
  "sha256": "c1ee8c73182006aacf12a52666b58e524967cd02726d16861e40d7f0e4e31339",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c-sharp",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "event_id": "used:cc:f4ff3c72e2a5e3e5:f275a489acbc523b:7684f49140d540dc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
  "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
  "pid": 1063497,
  "sha256": "00c83c8a2b4cbb6b92b2d4db23d2936ee020f06b210d691b529db35bcbd64f3f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c-sharp",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "event_id": "used:cc:f4ff3c72e2a5e3e5:f9a0c377e816b227:7684f49140d540dc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
  "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
  "pid": 1063497,
  "sha256": "866807c400288c991fa76ca160d42202c6b8bd949bde440107fcf934026cefc6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c-sharp",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "event_id": "used:cc:f4ff3c72e2a5e3e5:614c9945c3b711b7:7684f49140d540dc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
  "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
  "pid": 1063497,
  "sha256": "f2ec4e068aa37747c0dc553aedbb6425497e5d7feeb9944b8967d14c5d4ecdb6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c-sharp",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "event_id": "used:cc:f4ff3c72e2a5e3e5:d48ba9a5d5fa4cf0:7684f49140d540dc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
  "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
  "pid": 1063497,
  "sha256": "9abc816bed1ba228ef6de1fb39d2aec6683a8a566f887ef1ee5c2ed384a0a799",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c-sharp",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "event_id": "used:cc:f4ff3c72e2a5e3e5:59626fa00106dbbf:7684f49140d540dc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
  "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
  "pid": 1063497,
  "sha256": "18c08f971b3c4d34ccb2515de5ca46f0f7795a2bcfeb49ed3eb2267bd04c8f14",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c-sharp",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "event_id": "used:cc:f4ff3c72e2a5e3e5:182cad6c388031cc:7684f49140d540dc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
  "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
  "pid": 1063497,
  "sha256": "c2f8b8d6f7ae7e0c4ee9524e6ace0554f10c1147f8b21cc25386cf083baa86d3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c-sharp",
  "cargo_pkg_version": "0.23.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "event_id": "used:cc:f4ff3c72e2a5e3e5:3b121379803ccf64:7684f49140d540dc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
  "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
  "pid": 1063497,
  "sha256": "2529d750052663d96e230de609f5809a33fb1665e238fdddb01946032d2f7dce",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
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
  "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "cargo_pkg_name": "tree-sitter-c-sharp",
  "cargo_pkg_version": "0.23.1",
  "context_path": "/tmp/native-trace-1062789-1783999241328/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-1062789-1783999241328/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 1063497,
  "ppid": 1063480,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn",
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
    "/target/debug/deps",
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
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-1063497-1783999245480160619.map",
  "pid": 1063497,
  "ppid": 1063480,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1063497-1783999245480160619.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
  "parse_error_count": 2,
  "parsed_event_count": 1139,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1141,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "olchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n19.438  rustc            1069245 1067201   0 \n19.453  sed              1069256 1068587   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n19.453  cat              1069257 1068587   0 /usr/bin/cat /proc/2240539/stat\n19.461  cat              1069259 1068587   0 /usr/bin/cat /proc/4193716/stat\n19.468  rustc            1069262 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zerocopy --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-0.8.54/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"simd\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"__internal_use_only_features_that_work_on_stable\", \"alloc\", \"derive\", \"float-nightly\", \"simd\", \"simd-nightl ...\n19.498  rustc            1069271 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_traits --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.19/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"i128\" --cfg feature=\"std\" ...\n19.535  cc               1069280 1068966   0 /tmp/native-trace-1065492-1783999255512/shims/cc -m64 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/rustcMQ72Yt/symbols.o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.build_script_build.2e01dedb9631007a-cgu /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.5j162o12s80rg0o64680w18i1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n19.539  cc               1069281 1069280   0 /usr/bin/cc -m64 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/rustcMQ72Yt/symbols.o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.build_script_build.2e01dedb9631007a-cgu /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.5j162o12s80rg0o64680w18i1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n19.552  collect2         1069283 1069281   0 \n19.556  ld.lld           1069285 1069283   0 \n19.560  rust-lld         1069285 1069283   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccZkbtga.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766 ... /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccZkbtga.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.564  cc               1069284 1067694   0 /tmp/native-trace-1064622-1783999252386/shims/cc -Wl,--version-script=/target/debug/deps/rustc82Sdf6/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc82Sdf6/symbols.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.00.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.01.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.02.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.03.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.04.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.05.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.06.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.07.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.08.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.09.rcgu.o /target/debug/deps/rustc82Sdf6/rmeta.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.7ljsxze9pwq2dm20frm1qr6ir.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-1ec2033142a5fc21.rlib ...\n19.615  cc               1069286 1069284   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc82Sdf6/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc82Sdf6/symbols.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.00.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.01.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.02.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.03.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.04.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.05.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.06.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.07.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.08.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.09.rcgu.o /target/debug/deps/rustc82Sdf6/rmeta.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.7ljsxze9pwq2dm20frm1qr6ir.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-1ec2033142a5fc21.rlib ...\n19.632  collect2         1069306 1069286   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccmJWvoz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libbytemuck_derive-5466a6355cb98ec9.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc82Sdf6/raw-dylibs ...\n19.653  cc               1069308 1069171   0 /tmp/native-trace-1065492-1783999255512/shims/cc -m64 /target/debug/build/paste-31ffdbce721d802e/rustcfoyaim/symbols.o /target/debug/build/paste-31ffdbce721d802e/build_script_build-31ffdbce721d802e.build_script_build.38b4b9528d6c99de-cgu.0.rcgu.o /target/debug/build/paste-31ffdbce721d802e/build_script_build-31ffdbce721d802e.0lttecwkxwnxltq1pot9j61od.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n19.660  cc               1069310 1069308   0 /usr/bin/cc -m64 /target/debug/build/paste-31ffdbce721d802e/rustcfoyaim/symbols.o /target/debug/build/paste-31ffdbce721d802e/build_script_build-31ffdbce721d802e.build_script_build.38b4b9528d6c99de-cgu.0.rcgu.o /target/debug/build/paste-31ffdbce721d802e/build_script_build-31ffdbce721d802e.0lttecwkxwnxltq1pot9j61od.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n19.671  collect2         1069314 1069310   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccZxA7jN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.685  ld.lld           1069315 1069314   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccZxA7jN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/paste-31ffdbce721d802e/build_script_build-31ffdbce721d802e ...\n19.689  rust-lld         1069315 1069314   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccZxA7jN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.707  ld.lld           1069307 1069306   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccmJWvoz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libbytemuck_derive-5466a6355cb98ec9.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc82Sdf6/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n19.713  rust-lld         1069307 1069306   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccmJWvoz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libbytemuck_derive-5466a6355cb98ec9.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n19.821  rustc            1069318 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n19.846  rustc            1069365 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name generic_array --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/generic-array-0.14.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"more_lengths\", \"serde\", \"zeroize\")) -C metadata=0ef46d5a65357cb2 ...\n19.902  cc               1069376 1067686   0 /tmp/native-trace-1064622-1783999252386/shims/cc -Wl,--version-script=/target/debug/deps/rustcOKoJL4/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcOKoJL4/symbols.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.14.rcgu.o ...\n19.905  cc               1069379 1069376   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcOKoJL4/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcOKoJL4/symbols.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.14.rcgu.o ...\n19.910  rustc            1069229 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_traits --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.19/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"i128\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"i128\", \"libm\", \"std\")) ...\n19.915  collect2         1069382 1069379   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccKDJecE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-115c43b16354d5e6.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcOKoJL4/raw-dylibs ...\n19.928  rustc            1069385 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n19.940  build-script-bu  1069391 1067201   0 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build-script-build\n19.962  rustc            1069393 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n19.995  ld.lld           1069384 1069382   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccKDJecE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-115c43b16354d5e6.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcOKoJL4/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n20.001  rust-lld         1069384 1069382   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccKDJecE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-115c43b16354d5e6.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n20.015  rustc            1069406 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name subtle --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/subtle-2.6.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"const-generics\", \"core_hint_black_box\", \"default\", \"i128\", \"nightly\", \"std\")) ...\n20.054  rustc            1069422 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n20.092  cc               1069435 1069245   0 /tmp/native-trace-1065492-1783999255512/shims/cc -m64 /target/debug/build/rustversion-6f30d7ce87b29d07/rustcySay00/symbols.o /target/debug/build/rustversion-6f30d7ce87b29d07/build_script_build-6f30d7ce87b29d07.build_script_build.f753716ebfa6585b-cgu.0.r /target/debug/build/rustversion-6f30d7ce87b29d07/build_script_build-6f30d7ce87b29d07.build_script_build.f753716ebfa6585b-cgu.1.r /target/debug/build/rustversion-6f30d7ce87b29d07/build_script_build-6f30d7ce87b29d07.7g5s3kdklkfc6u5ogdlddzl3f.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n20.093  cc               1069436 1069435   0 /usr/bin/cc -m64 /target/debug/build/rustversion-6f30d7ce87b29d07/rustcySay00/symbols.o /target/debug/build/rustversion-6f30d7ce87b29d07/build_script_build-6f30d7ce87b29d07.build_script_build.f753716ebfa6585b-cgu.0.r /target/debug/build/rustversion-6f30d7ce87b29d07/build_script_build-6f30d7ce87b29d07.build_script_build.f753716ebfa6585b-cgu.1.r /target/debug/build/rustversion-6f30d7ce87b29d07/build_script_build-6f30d7ce87b29d07.7g5s3kdklkfc6u5ogdlddzl3f.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n20.112  collect2         1069442 1069436   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccEzpM38.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n20.119  ld.lld           1069443 1069442   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccEzpM38.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rustversion-6f30d7ce87b29d07/build_script_build-6f30d7ce87b29d07 ...\n20.119  build-script-bu  1069441 1067201   0 /target/debug/build/paste-31ffdbce721d802e/build-script-build\n20.122  rust-lld         1069443 1069442   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccEzpM38.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n20.123  rustc            1069444 1069441   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n20.167  rustc            1069467 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name paste --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/paste-1.0.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n20.226  rustc            1069474 1064775   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bytemuck --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bytemuck-1.25.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --deny=unexpected_cfgs --check-cfg cfg(target_arch, values(\"spirv\")) --cfg feature=\"bytemuck_derive\" --cfg ...\n20.282  cc               1069486 1069422   0 /tmp/native-trace-1065492-1783999255512/shims/cc -m64 /target/debug/build/crossbeam-deque-936e573f06352a39/rustcD05ZMw/symbols.o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.build_script_build.125d8aaaaa3abbde-cgu /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.2vbz55vvcr1pkfsulhrzgf6u9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n20.284  rustc            1069485 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_epoch --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n20.339  cc               1069492 1069486   0 /usr/bin/cc -m64 /target/debug/build/crossbeam-deque-936e573f06352a39/rustcD05ZMw/symbols.o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.build_script_build.125d8aaaaa3abbde-cgu /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.2vbz55vvcr1pkfsulhrzgf6u9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n20.350  collect2         1069498 1069492   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfvUnia.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n20.354  ld.lld           1069502 1069498   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfvUnia.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39 ...\n20.355  build-script-bu  1069497 1067201   0 /target/debug/build/rustversion-6f30d7ce87b29d07/build-script-build\n20.359  rust-lld         1069502 1069498   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfvUnia.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n20.362  rustc            1069503 1069497   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n20.431  rustc            1069529 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n20.432  rustc            1069532 1064775   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=8f32555af3826e92 ...\n20.453  rustc            1069535 1067201   0 \n20.506  runc             1069552 1057645   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/122ae5947c070a90f9d5b8d5f4a222dff7ea14dbb931703074e85b3c4d3 --log-format json --systemd-cgroup kill --all 122ae5947c070a90f9d5b8d5f4a222dff7ea14dbb931703074e85b3c4d3c236d 9\n20.526  rustc            1069557 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name digest --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/digest-0.9.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"blobby\", \"dev\", \"std\")) -C metadata=fcf87d0c9e847168 ...\n20.668  runc             1069585 1057645   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/122ae5947c070a90f9d5b8d5f4a222dff7ea14dbb931703074e85b3c4d3 --log-format json --systemd-cgroup delete 122ae5947c070a90f9d5b8d5f4a222dff7ea14dbb931703074e85b3c4d3c236d\n20.679  runc             1069591 1057604   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/35c563e1c1f6b0181a6b7e2d3f96d243126215e557090876660c46bcb67 --log-format json --systemd-cgroup kill --all 35c563e1c1f6b0181a6b7e2d3f96d243126215e557090876660c46bcb67994d3 9\n20.708  rustc            1069600 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libsecp256k1_core --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libsecp256k1-core-0.2.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n20.719  runc             1069601 1057604   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/35c563e1c1f6b0181a6b7e2d3f96d243126215e557090876660c46bcb67 --log-format json --systemd-cgroup delete 35c563e1c1f6b0181a6b7e2d3f96d243126215e557090876660c46bcb67994d3\n20.730  build-script-bu  1069609 1067201   0 /target/debug/build/crossbeam-deque-936e573f06352a39/build-script-build\n20.752  rustc            1069611 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name itertools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"use_alloc\" --cfg feature=\"use_std\" ...\n20.764  rustc            1069617 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name winnow --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winnow-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::wildcard_imports --warn=clippy::verbose_file_reads --warn=unused_macro_rules --warn=unused_lifetimes ...\n20.800  containerd-shim  1069623 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 122ae5947c070a90f9d5b8d5f4a222dff7ea14dbb931703074e85b3c4d3c236d -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/122ae5947c070a90f9d5b8d5f4a222dff7ea14dbb931703074e85b3c4d3 delete\n20.804  runc             1069630 1069623   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/122ae5947c070a90f9d5b8d5f4a222dff7ea14dbb931703074e85b3c4d3c236 --log-format json delete --force 122ae5947c070a90f9d5b8d5f4a222dff7ea14dbb931703074e85b3c4d3c236d\n20.824  rustc            1069643 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_integer --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"i128\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n20.836  cc               1069635 1067692   0 /tmp/native-trace-1064622-1783999252386/shims/cc -Wl,--version-script=/target/debug/deps/rustcXN2T42/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcXN2T42/symbols.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.00.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.01.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.02.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.03.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.04.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.05.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.06.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.07.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.08.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.09.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.10.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.11.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.12.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.13.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.14.rcgu.o ...\n20.839  cc               1069646 1069635   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcXN2T42/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcXN2T42/symbols.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.00.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.01.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.02.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.03.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.04.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.05.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.06.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.07.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.08.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.09.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.10.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.11.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.12.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.13.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.14.rcgu.o ...\n20.845  collect2         1069648 1069646   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjTYUjQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libborsh_derive-c439346356cf72b2.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcXN2T42/raw-dylibs ...\n20.848  ld.lld           1069649 1069648   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjTYUjQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libborsh_derive-c439346356cf72b2.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcXN2T42/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n20.849  rust-lld         1069649 1069648   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjTYUjQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libborsh_derive-c439346356cf72b2.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n20.871  systemd-sysctl   1069656 1068199   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth894410c --prefix=/net/ipv4/neigh/veth894410c --prefix=/net/ipv6/conf/veth894410c --prefix=/net/ipv6/neigh/veth894410c\n20.892  rustc            1069655 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.13.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"web_spin_lock\")) -C metadata=03837be89c98692f ...\n21.009  containerd-shim  1069690 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 35c563e1c1f6b0181a6b7e2d3f96d243126215e557090876660c46bcb67994d3 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/35c563e1c1f6b0181a6b7e2d3f96d243126215e557090876660c46bcb67 delete\n21.015  runc             1069699 1069690   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/35c563e1c1f6b0181a6b7e2d3f96d243126215e557090876660c46bcb67994d --log-format json delete --force 35c563e1c1f6b0181a6b7e2d3f96d243126215e557090876660c46bcb67994d3\n21.031  cc               1069704 1069655   0 /tmp/native-trace-1065492-1783999255512/shims/cc -m64 /target/debug/build/rayon-core-7298df1456a2eabf/rustc8CFzJX/symbols.o /target/debug/build/rayon-core-7298df1456a2eabf/build_script_build-7298df1456a2eabf.build_script_build.3834727be9719ab3-cgu.0.rc /target/debug/build/rayon-core-7298df1456a2eabf/build_script_build-7298df1456a2eabf.3a1uctql37wnk23nrc6d4uvrf.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n21.034  cc               1069705 1069704   0 /usr/bin/cc -m64 /target/debug/build/rayon-core-7298df1456a2eabf/rustc8CFzJX/symbols.o /target/debug/build/rayon-core-7298df1456a2eabf/build_script_build-7298df1456a2eabf.build_script_build.3834727be9719ab3-cgu.0.rc /target/debug/build/rayon-core-7298df1456a2eabf/build_script_build-7298df1456a2eabf.3a1uctql37wnk23nrc6d4uvrf.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n21.054  collect2         1069708 1069705   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccvromNW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.057  ld.lld           1069709 1069708   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccvromNW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rayon-core-7298df1456a2eabf/build_script_build-7298df1456a2eabf ...\n21.060  rust-lld         1069709 1069708   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccvromNW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.061  rustc            1069707 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name equivalent --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/equivalent-1.0.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=2cf8af21ad83c5b4 ...\n21.063  systemd-sysctl   1069710 1068199   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth80507b3 --prefix=/net/ipv4/neigh/veth80507b3 --prefix=/net/ipv6/conf/veth80507b3 --prefix=/net/ipv6/neigh/veth80507b3\n21.085  cc               1069712 1067914   0 /tmp/native-trace-1064622-1783999252386/shims/cc -Wl,--version-script=/target/debug/deps/rustcBfltGT/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcBfltGT/symbols.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.00.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.01.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.02.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.03.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.04.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.05.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.06.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.07.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.08.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.09.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.10.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.11.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.12.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.13.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.14.rcgu.o ...\n21.087  cc               1069713 1069712   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcBfltGT/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcBfltGT/symbols.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.00.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.01.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.02.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.03.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.04.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.05.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.06.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.07.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.08.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.09.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.10.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.11.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.12.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.13.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.14.rcgu.o ...\n21.094  collect2         1069728 1069713   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cckf6hLT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libderivative-8324aee1640033d9.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcBfltGT/raw-dylibs ...\n21.098  ld.lld           1069734 1069728   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cckf6hLT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libderivative-8324aee1640033d9.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcBfltGT/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n21.107  rust-lld         1069734 1069728   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cckf6hLT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libderivative-8324aee1640033d9.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n21.151  rustc            1069695 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_integer --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"i128\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"i128\", \"std\")) ...\n21.154  cc               1069735 1069467   0 /tmp/native-trace-1065492-1783999255512/shims/cc -Wl,--version-script=/target/debug/deps/rustcHYzDxd/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcHYzDxd/symbols.o /target/debug/deps/paste-03c817d525241eb1.paste.7d17f67ab1fdb7a8-cgu.0.rcgu.o /target/debug/deps/paste-03c817d525241eb1.paste.7d17f67ab1fdb7a8-cgu.1.rcgu.o /target/debug/deps/paste-03c817d525241eb1.paste.7d17f67ab1fdb7a8-cgu.2.rcgu.o /target/debug/deps/paste-03c817d525241eb1.paste.7d17f67ab1fdb7a8-cgu.3.rcgu.o /target/debug/deps/paste-03c817d525241eb1.paste.7d17f67ab1fdb7a8-cgu.4.rcgu.o /target/debug/deps/paste-03c817d525241eb1.paste.7d17f67ab1fdb7a8-cgu.5.rcgu.o /target/debug/deps/paste-03c817d525241eb1.paste.7d17f67ab1fdb7a8-cgu.6.rcgu.o /target/debug/deps/paste-03c817d525241eb1.paste.7d17f67ab1fdb7a8-cgu.7.rcgu.o /target/debug/deps/rustcHYzDxd/rmeta.o /target/debug/deps/paste-03c817d525241eb1.drlfcgls4tmd2yug9nv0uklnt.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n21.161  rustc            1069741 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hashbrown --edition=2024 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.17.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unused_extern_crates --warn=unsafe_op_in_unsafe_fn --warn=unreachable_pub --warn=clippy::str_to_string --warn=clippy::semicolon_if_nothing_returned --warn=clippy::ref_as_ptr ...\n"
}
```

#### Record 28

```json
{
  "argv": [
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063415,
  "build_script_target_dir": "tree-sitter-language-04f523abf8aa8aa2",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build",
  "pid": 1063415,
  "ppid": 1063357,
  "root_cargo_pid": 1063357,
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
    "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063518,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build-script-build",
  "pid": 1063518,
  "ppid": 1063357,
  "root_cargo_pid": 1063357,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out"
}
```

#### Record 30

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-E",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/8236753969842890862detect_compiler_fami"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063518,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 1063519,
  "ppid": 1063518,
  "root_cargo_pid": 1063357,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 31

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
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/8236753969842890862detect_compiler_fami",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-dumpbase",
    "8236753969842890862detect_compiler_family.c",
    "-dumpbase-ext",
    ".c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063518,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 1063520,
  "ppid": 1063519,
  "root_cargo_pid": 1063357,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 32

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063518,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 1063521,
  "ppid": 1063518,
  "root_cargo_pid": 1063357,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 33

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-E",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/5787956455649300018detect_compiler_fami"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063518,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 1063522,
  "ppid": 1063518,
  "root_cargo_pid": 1063357,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 34

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
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/5787956455649300018detect_compiler_fami",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-dumpbase",
    "5787956455649300018detect_compiler_family.c",
    "-dumpbase-ext",
    ".c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063518,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 1063523,
  "ppid": 1063522,
  "root_cargo_pid": 1063357,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 35

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063518,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 1063524,
  "ppid": 1063518,
  "root_cargo_pid": 1063357,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 36

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-Wall",
    "-Wextra",
    "-Wno-unused-value",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/flag_check",
    "-c",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/flag_check.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063518,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 1063525,
  "ppid": 1063518,
  "root_cargo_pid": 1063357,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 37

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/flag_check.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/",
    "-dumpbase",
    "flag_check.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "-O0",
    "-Wall",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063518,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 1063526,
  "ppid": 1063525,
  "root_cargo_pid": 1063357,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 38

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/flag_check",
    "/tmp/cc2YtBBh.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063518,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 1063527,
  "ppid": 1063525,
  "root_cargo_pid": 1063357,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_cwd_recovered_from_compiler_parent": true
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
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-std=c11",
    "-I",
    "src",
    "-Wall",
    "-Wextra",
    "-Wno-unused-value",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-parser.o",
    "-c",
    "src/parser.c",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063518,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 1063528,
  "ppid": 1063518,
  "root_cargo_pid": 1063357,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "src",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "src/parser.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/",
    "-dumpbase",
    "ea708c7824d36062-parser.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063518,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 1063529,
  "ppid": 1063528,
  "root_cargo_pid": 1063357,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 41

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-I",
    "src",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-parser.o",
    "/tmp/cc2DdQzG.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063518,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 1064067,
  "ppid": 1063528,
  "root_cargo_pid": 1063357,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-std=c11",
    "-I",
    "src",
    "-Wall",
    "-Wextra",
    "-Wno-unused-value",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-scanner.o",
    "-c",
    "src/scanner.c",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063518,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 1064068,
  "ppid": 1063518,
  "root_cargo_pid": 1063357,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
    "src",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "src/scanner.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/",
    "-dumpbase",
    "ea708c7824d36062-scanner.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063518,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 1064069,
  "ppid": 1064068,
  "root_cargo_pid": 1063357,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 44

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-I",
    "src",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-scanner.o",
    "/tmp/cctYRJTb.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063518,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 1064070,
  "ppid": 1064068,
  "root_cargo_pid": 1063357,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 45

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "cqD",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/libtree-sitter-c-sharp.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-parser.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-scanner.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063518,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-ar",
  "pid": 1064071,
  "ppid": 1063518,
  "root_cargo_pid": 1063357,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 46

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "sD",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/libtree-sitter-c-sharp.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1063518,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-ar",
  "pid": 1064072,
  "ppid": 1063518,
  "root_cargo_pid": 1063357,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
  "crate": "tree-sitter-c-sharp",
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "event_id": "bsrun:0e7f7ba30e356f07:25c8fc3cd2a08df6:6aca8841193a6edb",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
  "success": true,
  "target": null,
  "version": "0.23.1",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  }
}
```

#### Record 49

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/flag_check.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/",
    "-dumpbase",
    "flag_check.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "-O0",
    "-Wall",
    "..."
  ],
  "src": "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/flag_check.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/flag_check",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 1063526,
  "ppid": 1063525,
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "root_cargo_pid": 1063357,
  "build_script_root_pid": 1063518,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 50

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "src",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "src/parser.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/",
    "-dumpbase",
    "ea708c7824d36062-parser.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "src/parser.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-parser.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 1063529,
  "ppid": 1063528,
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "root_cargo_pid": 1063357,
  "build_script_root_pid": 1063518,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 51

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "src",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "src/scanner.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/",
    "-dumpbase",
    "ea708c7824d36062-scanner.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "src/scanner.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-scanner.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 1064069,
  "ppid": 1064068,
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "root_cargo_pid": 1063357,
  "build_script_root_pid": 1063518,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 52

```json
{
  "event": "archive",
  "tool": "/usr/bin/riscv64-linux-gnu-ar",
  "real_tool": "/usr/bin/riscv64-linux-gnu-ar",
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "cqD",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/libtree-sitter-c-sharp.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-parser.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-scanner.o"
  ],
  "archive": "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/libtree-sitter-c-sharp.a",
  "objects": [
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-parser.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-scanner.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 1064071,
  "ppid": 1063518,
  "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "root_cargo_pid": 1063357,
  "build_script_root_pid": 1063518,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
  "_owner": {
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
    "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T03:21:11.250171+00:00",
  "crate": "tree-sitter-c-sharp",
  "version": "0.23.1",
  "architecture": "riscv64",
  "duration_seconds": 35.133349793963134,
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
        "crate": "tree-sitter-c-sharp",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
        "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
        "manifest_path": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1/Cargo.toml"
      }
    ],
    "attributed_event_count": 27,
    "unattributed_event_count": 21,
    "owners": [
      {
        "crate": "tree-sitter-c-sharp",
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
      "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "workspace_root": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1"
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
          "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
          "name": "tree-sitter-c-sharp",
          "version": "0.23.1",
          "manifest_path": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
          "name": "tree-sitter-language",
          "version": "0.1.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7"
        }
      ],
      "_owner": {
        "crate": "tree-sitter-c-sharp",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
        "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/raw-dylibs",
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
      "pid": 1063384,
      "ppid": 1063370,
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/raw-dylibs",
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
      "event_id": "used:cc:d9861ad91616b5cc:edfd328aa6753eb2:085e3bf50b18abef",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
      "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o",
      "pid": 1063384,
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/raw-dylibs",
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
      "pid": 1063384,
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/raw-dylibs",
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
      "pid": 1063384,
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/raw-dylibs",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/raw-dylibs",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/raw-dylibs",
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
      "context_path": "/tmp/native-trace-1062789-1783999241328/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-1062789-1783999241328/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 1063384,
      "ppid": 1063370,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/raw-dylibs",
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
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2",
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
          "directory": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o",
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
      "map_path": "/tmp/native-trace-link-cc-1063384-1783999244726377014.map",
      "pid": 1063384,
      "ppid": 1063370,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-1063384-1783999244726377014.map"
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
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "exit_code": 0,
      "kind": "exec",
      "pid": 1063497,
      "ppid": 1063480,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c-sharp",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
        "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c-sharp",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "event_id": "used:cc:f4ff3c72e2a5e3e5:43a23aa3f5603b47:7684f49140d540dc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
      "pid": 1063497,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c-sharp",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
        "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c-sharp",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "event_id": "used:cc:f4ff3c72e2a5e3e5:1e7b026ec3865928:7684f49140d540dc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
      "pid": 1063497,
      "sha256": "f5ee8725de09ccf42aeba66c08cdd18121cd1dcdd39ff76d1fb485f89195fe0e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c-sharp",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
        "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c-sharp",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "event_id": "used:cc:f4ff3c72e2a5e3e5:7a8eada1e9059940:7684f49140d540dc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
      "pid": 1063497,
      "sha256": "4a9e60b0dafa512317278b5221b41047d38f1b257caaa50c03a6b3008f5b7a1c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c-sharp",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
        "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c-sharp",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "event_id": "used:cc:f4ff3c72e2a5e3e5:4d36d936a59ae38a:7684f49140d540dc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
      "pid": 1063497,
      "sha256": "55f8e13c92b124d990f5be26ef09dadc3a4409420bf448cd18739b42303a8e0e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c-sharp",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
        "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c-sharp",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "event_id": "used:cc:f4ff3c72e2a5e3e5:c38bd32db620722a:7684f49140d540dc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
      "pid": 1063497,
      "sha256": "7d0dd79164003bd8fdbb94fb93727de8cf9a5612cebb8fc2a14b7e5b3cf71a27",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c-sharp",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
        "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c-sharp",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "event_id": "used:cc:f4ff3c72e2a5e3e5:52e81273f2ea2cde:7684f49140d540dc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
      "pid": 1063497,
      "sha256": "c1ee8c73182006aacf12a52666b58e524967cd02726d16861e40d7f0e4e31339",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c-sharp",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
        "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c-sharp",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "event_id": "used:cc:f4ff3c72e2a5e3e5:f275a489acbc523b:7684f49140d540dc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
      "pid": 1063497,
      "sha256": "00c83c8a2b4cbb6b92b2d4db23d2936ee020f06b210d691b529db35bcbd64f3f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c-sharp",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
        "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c-sharp",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "event_id": "used:cc:f4ff3c72e2a5e3e5:f9a0c377e816b227:7684f49140d540dc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
      "pid": 1063497,
      "sha256": "866807c400288c991fa76ca160d42202c6b8bd949bde440107fcf934026cefc6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c-sharp",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
        "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c-sharp",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "event_id": "used:cc:f4ff3c72e2a5e3e5:614c9945c3b711b7:7684f49140d540dc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
      "pid": 1063497,
      "sha256": "f2ec4e068aa37747c0dc553aedbb6425497e5d7feeb9944b8967d14c5d4ecdb6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c-sharp",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
        "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c-sharp",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "event_id": "used:cc:f4ff3c72e2a5e3e5:d48ba9a5d5fa4cf0:7684f49140d540dc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
      "pid": 1063497,
      "sha256": "9abc816bed1ba228ef6de1fb39d2aec6683a8a566f887ef1ee5c2ed384a0a799",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c-sharp",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
        "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c-sharp",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "event_id": "used:cc:f4ff3c72e2a5e3e5:59626fa00106dbbf:7684f49140d540dc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
      "pid": 1063497,
      "sha256": "18c08f971b3c4d34ccb2515de5ca46f0f7795a2bcfeb49ed3eb2267bd04c8f14",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c-sharp",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
        "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c-sharp",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "event_id": "used:cc:f4ff3c72e2a5e3e5:182cad6c388031cc:7684f49140d540dc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
      "pid": 1063497,
      "sha256": "c2f8b8d6f7ae7e0c4ee9524e6ace0554f10c1147f8b21cc25386cf083baa86d3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c-sharp",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
        "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c-sharp",
      "cargo_pkg_version": "0.23.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "event_id": "used:cc:f4ff3c72e2a5e3e5:3b121379803ccf64:7684f49140d540dc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
      "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
      "pid": 1063497,
      "sha256": "2529d750052663d96e230de609f5809a33fb1665e238fdddb01946032d2f7dce",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c-sharp",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
        "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
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
      "output": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c-sharp",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
        "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "cargo_pkg_name": "tree-sitter-c-sharp",
      "cargo_pkg_version": "0.23.1",
      "context_path": "/tmp/native-trace-1062789-1783999241328/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-1062789-1783999241328/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 1063497,
      "ppid": 1063480,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "_owner": {
        "crate": "tree-sitter-c-sharp",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
        "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn",
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
        "/target/debug/deps",
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
          "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-1063497-1783999245480160619.map",
      "pid": 1063497,
      "ppid": 1063480,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-1063497-1783999245480160619.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "tree-sitter-c-sharp",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
        "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
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
      "parsed_event_count": 1139,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1141,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "olchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n19.438  rustc            1069245 1067201   0 \n19.453  sed              1069256 1068587   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n19.453  cat              1069257 1068587   0 /usr/bin/cat /proc/2240539/stat\n19.461  cat              1069259 1068587   0 /usr/bin/cat /proc/4193716/stat\n19.468  rustc            1069262 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zerocopy --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-0.8.54/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"simd\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"__internal_use_only_features_that_work_on_stable\", \"alloc\", \"derive\", \"float-nightly\", \"simd\", \"simd-nightl ...\n19.498  rustc            1069271 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_traits --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.19/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"i128\" --cfg feature=\"std\" ...\n19.535  cc               1069280 1068966   0 /tmp/native-trace-1065492-1783999255512/shims/cc -m64 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/rustcMQ72Yt/symbols.o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.build_script_build.2e01dedb9631007a-cgu /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.5j162o12s80rg0o64680w18i1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n19.539  cc               1069281 1069280   0 /usr/bin/cc -m64 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/rustcMQ72Yt/symbols.o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.build_script_build.2e01dedb9631007a-cgu /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.5j162o12s80rg0o64680w18i1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n19.552  collect2         1069283 1069281   0 \n19.556  ld.lld           1069285 1069283   0 \n19.560  rust-lld         1069285 1069283   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccZkbtga.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766 ... /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccZkbtga.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.564  cc               1069284 1067694   0 /tmp/native-trace-1064622-1783999252386/shims/cc -Wl,--version-script=/target/debug/deps/rustc82Sdf6/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc82Sdf6/symbols.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.00.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.01.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.02.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.03.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.04.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.05.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.06.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.07.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.08.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.09.rcgu.o /target/debug/deps/rustc82Sdf6/rmeta.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.7ljsxze9pwq2dm20frm1qr6ir.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-1ec2033142a5fc21.rlib ...\n19.615  cc               1069286 1069284   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc82Sdf6/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc82Sdf6/symbols.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.00.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.01.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.02.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.03.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.04.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.05.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.06.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.07.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.08.rcgu.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.bytemuck_derive.2b413f6a06734f95-cgu.09.rcgu.o /target/debug/deps/rustc82Sdf6/rmeta.o /target/debug/deps/bytemuck_derive-5466a6355cb98ec9.7ljsxze9pwq2dm20frm1qr6ir.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-1ec2033142a5fc21.rlib ...\n19.632  collect2         1069306 1069286   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccmJWvoz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libbytemuck_derive-5466a6355cb98ec9.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc82Sdf6/raw-dylibs ...\n19.653  cc               1069308 1069171   0 /tmp/native-trace-1065492-1783999255512/shims/cc -m64 /target/debug/build/paste-31ffdbce721d802e/rustcfoyaim/symbols.o /target/debug/build/paste-31ffdbce721d802e/build_script_build-31ffdbce721d802e.build_script_build.38b4b9528d6c99de-cgu.0.rcgu.o /target/debug/build/paste-31ffdbce721d802e/build_script_build-31ffdbce721d802e.0lttecwkxwnxltq1pot9j61od.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n19.660  cc               1069310 1069308   0 /usr/bin/cc -m64 /target/debug/build/paste-31ffdbce721d802e/rustcfoyaim/symbols.o /target/debug/build/paste-31ffdbce721d802e/build_script_build-31ffdbce721d802e.build_script_build.38b4b9528d6c99de-cgu.0.rcgu.o /target/debug/build/paste-31ffdbce721d802e/build_script_build-31ffdbce721d802e.0lttecwkxwnxltq1pot9j61od.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n19.671  collect2         1069314 1069310   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccZxA7jN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.685  ld.lld           1069315 1069314   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccZxA7jN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/paste-31ffdbce721d802e/build_script_build-31ffdbce721d802e ...\n19.689  rust-lld         1069315 1069314   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccZxA7jN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.707  ld.lld           1069307 1069306   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccmJWvoz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libbytemuck_derive-5466a6355cb98ec9.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc82Sdf6/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n19.713  rust-lld         1069307 1069306   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccmJWvoz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libbytemuck_derive-5466a6355cb98ec9.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n19.821  rustc            1069318 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n19.846  rustc            1069365 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name generic_array --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/generic-array-0.14.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"more_lengths\", \"serde\", \"zeroize\")) -C metadata=0ef46d5a65357cb2 ...\n19.902  cc               1069376 1067686   0 /tmp/native-trace-1064622-1783999252386/shims/cc -Wl,--version-script=/target/debug/deps/rustcOKoJL4/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcOKoJL4/symbols.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.14.rcgu.o ...\n19.905  cc               1069379 1069376   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcOKoJL4/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcOKoJL4/symbols.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.14.rcgu.o ...\n19.910  rustc            1069229 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_traits --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.19/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"i128\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"i128\", \"libm\", \"std\")) ...\n19.915  collect2         1069382 1069379   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccKDJecE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-115c43b16354d5e6.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcOKoJL4/raw-dylibs ...\n19.928  rustc            1069385 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n19.940  build-script-bu  1069391 1067201   0 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build-script-build\n19.962  rustc            1069393 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n19.995  ld.lld           1069384 1069382   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccKDJecE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-115c43b16354d5e6.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcOKoJL4/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n20.001  rust-lld         1069384 1069382   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccKDJecE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-115c43b16354d5e6.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n20.015  rustc            1069406 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name subtle --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/subtle-2.6.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"const-generics\", \"core_hint_black_box\", \"default\", \"i128\", \"nightly\", \"std\")) ...\n20.054  rustc            1069422 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n20.092  cc               1069435 1069245   0 /tmp/native-trace-1065492-1783999255512/shims/cc -m64 /target/debug/build/rustversion-6f30d7ce87b29d07/rustcySay00/symbols.o /target/debug/build/rustversion-6f30d7ce87b29d07/build_script_build-6f30d7ce87b29d07.build_script_build.f753716ebfa6585b-cgu.0.r /target/debug/build/rustversion-6f30d7ce87b29d07/build_script_build-6f30d7ce87b29d07.build_script_build.f753716ebfa6585b-cgu.1.r /target/debug/build/rustversion-6f30d7ce87b29d07/build_script_build-6f30d7ce87b29d07.7g5s3kdklkfc6u5ogdlddzl3f.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n20.093  cc               1069436 1069435   0 /usr/bin/cc -m64 /target/debug/build/rustversion-6f30d7ce87b29d07/rustcySay00/symbols.o /target/debug/build/rustversion-6f30d7ce87b29d07/build_script_build-6f30d7ce87b29d07.build_script_build.f753716ebfa6585b-cgu.0.r /target/debug/build/rustversion-6f30d7ce87b29d07/build_script_build-6f30d7ce87b29d07.build_script_build.f753716ebfa6585b-cgu.1.r /target/debug/build/rustversion-6f30d7ce87b29d07/build_script_build-6f30d7ce87b29d07.7g5s3kdklkfc6u5ogdlddzl3f.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n20.112  collect2         1069442 1069436   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccEzpM38.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n20.119  ld.lld           1069443 1069442   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccEzpM38.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rustversion-6f30d7ce87b29d07/build_script_build-6f30d7ce87b29d07 ...\n20.119  build-script-bu  1069441 1067201   0 /target/debug/build/paste-31ffdbce721d802e/build-script-build\n20.122  rust-lld         1069443 1069442   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccEzpM38.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n20.123  rustc            1069444 1069441   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n20.167  rustc            1069467 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name paste --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/paste-1.0.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n20.226  rustc            1069474 1064775   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bytemuck --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bytemuck-1.25.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --deny=unexpected_cfgs --check-cfg cfg(target_arch, values(\"spirv\")) --cfg feature=\"bytemuck_derive\" --cfg ...\n20.282  cc               1069486 1069422   0 /tmp/native-trace-1065492-1783999255512/shims/cc -m64 /target/debug/build/crossbeam-deque-936e573f06352a39/rustcD05ZMw/symbols.o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.build_script_build.125d8aaaaa3abbde-cgu /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.2vbz55vvcr1pkfsulhrzgf6u9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n20.284  rustc            1069485 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_epoch --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n20.339  cc               1069492 1069486   0 /usr/bin/cc -m64 /target/debug/build/crossbeam-deque-936e573f06352a39/rustcD05ZMw/symbols.o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.build_script_build.125d8aaaaa3abbde-cgu /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.2vbz55vvcr1pkfsulhrzgf6u9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n20.350  collect2         1069498 1069492   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfvUnia.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n20.354  ld.lld           1069502 1069498   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfvUnia.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39 ...\n20.355  build-script-bu  1069497 1067201   0 /target/debug/build/rustversion-6f30d7ce87b29d07/build-script-build\n20.359  rust-lld         1069502 1069498   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfvUnia.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n20.362  rustc            1069503 1069497   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n20.431  rustc            1069529 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n20.432  rustc            1069532 1064775   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=8f32555af3826e92 ...\n20.453  rustc            1069535 1067201   0 \n20.506  runc             1069552 1057645   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/122ae5947c070a90f9d5b8d5f4a222dff7ea14dbb931703074e85b3c4d3 --log-format json --systemd-cgroup kill --all 122ae5947c070a90f9d5b8d5f4a222dff7ea14dbb931703074e85b3c4d3c236d 9\n20.526  rustc            1069557 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name digest --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/digest-0.9.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"blobby\", \"dev\", \"std\")) -C metadata=fcf87d0c9e847168 ...\n20.668  runc             1069585 1057645   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/122ae5947c070a90f9d5b8d5f4a222dff7ea14dbb931703074e85b3c4d3 --log-format json --systemd-cgroup delete 122ae5947c070a90f9d5b8d5f4a222dff7ea14dbb931703074e85b3c4d3c236d\n20.679  runc             1069591 1057604   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/35c563e1c1f6b0181a6b7e2d3f96d243126215e557090876660c46bcb67 --log-format json --systemd-cgroup kill --all 35c563e1c1f6b0181a6b7e2d3f96d243126215e557090876660c46bcb67994d3 9\n20.708  rustc            1069600 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libsecp256k1_core --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libsecp256k1-core-0.2.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n20.719  runc             1069601 1057604   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/35c563e1c1f6b0181a6b7e2d3f96d243126215e557090876660c46bcb67 --log-format json --systemd-cgroup delete 35c563e1c1f6b0181a6b7e2d3f96d243126215e557090876660c46bcb67994d3\n20.730  build-script-bu  1069609 1067201   0 /target/debug/build/crossbeam-deque-936e573f06352a39/build-script-build\n20.752  rustc            1069611 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name itertools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"use_alloc\" --cfg feature=\"use_std\" ...\n20.764  rustc            1069617 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name winnow --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winnow-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=clippy::zero_sized_map_values --warn=clippy::wildcard_imports --warn=clippy::verbose_file_reads --warn=unused_macro_rules --warn=unused_lifetimes ...\n20.800  containerd-shim  1069623 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 122ae5947c070a90f9d5b8d5f4a222dff7ea14dbb931703074e85b3c4d3c236d -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/122ae5947c070a90f9d5b8d5f4a222dff7ea14dbb931703074e85b3c4d3 delete\n20.804  runc             1069630 1069623   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/122ae5947c070a90f9d5b8d5f4a222dff7ea14dbb931703074e85b3c4d3c236 --log-format json delete --force 122ae5947c070a90f9d5b8d5f4a222dff7ea14dbb931703074e85b3c4d3c236d\n20.824  rustc            1069643 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_integer --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"i128\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n20.836  cc               1069635 1067692   0 /tmp/native-trace-1064622-1783999252386/shims/cc -Wl,--version-script=/target/debug/deps/rustcXN2T42/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcXN2T42/symbols.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.00.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.01.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.02.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.03.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.04.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.05.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.06.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.07.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.08.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.09.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.10.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.11.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.12.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.13.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.14.rcgu.o ...\n20.839  cc               1069646 1069635   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcXN2T42/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcXN2T42/symbols.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.00.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.01.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.02.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.03.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.04.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.05.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.06.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.07.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.08.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.09.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.10.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.11.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.12.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.13.rcgu.o /target/debug/deps/borsh_derive-c439346356cf72b2.borsh_derive.90e7f304f4838555-cgu.14.rcgu.o ...\n20.845  collect2         1069648 1069646   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjTYUjQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libborsh_derive-c439346356cf72b2.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcXN2T42/raw-dylibs ...\n20.848  ld.lld           1069649 1069648   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjTYUjQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libborsh_derive-c439346356cf72b2.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcXN2T42/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n20.849  rust-lld         1069649 1069648   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjTYUjQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libborsh_derive-c439346356cf72b2.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n20.871  systemd-sysctl   1069656 1068199   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth894410c --prefix=/net/ipv4/neigh/veth894410c --prefix=/net/ipv6/conf/veth894410c --prefix=/net/ipv6/neigh/veth894410c\n20.892  rustc            1069655 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.13.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"web_spin_lock\")) -C metadata=03837be89c98692f ...\n21.009  containerd-shim  1069690 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 35c563e1c1f6b0181a6b7e2d3f96d243126215e557090876660c46bcb67994d3 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/35c563e1c1f6b0181a6b7e2d3f96d243126215e557090876660c46bcb67 delete\n21.015  runc             1069699 1069690   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/35c563e1c1f6b0181a6b7e2d3f96d243126215e557090876660c46bcb67994d --log-format json delete --force 35c563e1c1f6b0181a6b7e2d3f96d243126215e557090876660c46bcb67994d3\n21.031  cc               1069704 1069655   0 /tmp/native-trace-1065492-1783999255512/shims/cc -m64 /target/debug/build/rayon-core-7298df1456a2eabf/rustc8CFzJX/symbols.o /target/debug/build/rayon-core-7298df1456a2eabf/build_script_build-7298df1456a2eabf.build_script_build.3834727be9719ab3-cgu.0.rc /target/debug/build/rayon-core-7298df1456a2eabf/build_script_build-7298df1456a2eabf.3a1uctql37wnk23nrc6d4uvrf.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n21.034  cc               1069705 1069704   0 /usr/bin/cc -m64 /target/debug/build/rayon-core-7298df1456a2eabf/rustc8CFzJX/symbols.o /target/debug/build/rayon-core-7298df1456a2eabf/build_script_build-7298df1456a2eabf.build_script_build.3834727be9719ab3-cgu.0.rc /target/debug/build/rayon-core-7298df1456a2eabf/build_script_build-7298df1456a2eabf.3a1uctql37wnk23nrc6d4uvrf.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n21.054  collect2         1069708 1069705   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccvromNW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.057  ld.lld           1069709 1069708   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccvromNW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rayon-core-7298df1456a2eabf/build_script_build-7298df1456a2eabf ...\n21.060  rust-lld         1069709 1069708   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccvromNW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.061  rustc            1069707 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name equivalent --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/equivalent-1.0.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=2cf8af21ad83c5b4 ...\n21.063  systemd-sysctl   1069710 1068199   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth80507b3 --prefix=/net/ipv4/neigh/veth80507b3 --prefix=/net/ipv6/conf/veth80507b3 --prefix=/net/ipv6/neigh/veth80507b3\n21.085  cc               1069712 1067914   0 /tmp/native-trace-1064622-1783999252386/shims/cc -Wl,--version-script=/target/debug/deps/rustcBfltGT/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcBfltGT/symbols.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.00.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.01.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.02.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.03.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.04.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.05.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.06.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.07.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.08.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.09.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.10.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.11.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.12.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.13.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.14.rcgu.o ...\n21.087  cc               1069713 1069712   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcBfltGT/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcBfltGT/symbols.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.00.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.01.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.02.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.03.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.04.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.05.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.06.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.07.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.08.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.09.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.10.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.11.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.12.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.13.rcgu.o /target/debug/deps/derivative-8324aee1640033d9.derivative.af02e39cc39e075-cgu.14.rcgu.o ...\n21.094  collect2         1069728 1069713   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cckf6hLT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libderivative-8324aee1640033d9.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcBfltGT/raw-dylibs ...\n21.098  ld.lld           1069734 1069728   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cckf6hLT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libderivative-8324aee1640033d9.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcBfltGT/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n21.107  rust-lld         1069734 1069728   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cckf6hLT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libderivative-8324aee1640033d9.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n21.151  rustc            1069695 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_integer --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"i128\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"i128\", \"std\")) ...\n21.154  cc               1069735 1069467   0 /tmp/native-trace-1065492-1783999255512/shims/cc -Wl,--version-script=/target/debug/deps/rustcHYzDxd/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcHYzDxd/symbols.o /target/debug/deps/paste-03c817d525241eb1.paste.7d17f67ab1fdb7a8-cgu.0.rcgu.o /target/debug/deps/paste-03c817d525241eb1.paste.7d17f67ab1fdb7a8-cgu.1.rcgu.o /target/debug/deps/paste-03c817d525241eb1.paste.7d17f67ab1fdb7a8-cgu.2.rcgu.o /target/debug/deps/paste-03c817d525241eb1.paste.7d17f67ab1fdb7a8-cgu.3.rcgu.o /target/debug/deps/paste-03c817d525241eb1.paste.7d17f67ab1fdb7a8-cgu.4.rcgu.o /target/debug/deps/paste-03c817d525241eb1.paste.7d17f67ab1fdb7a8-cgu.5.rcgu.o /target/debug/deps/paste-03c817d525241eb1.paste.7d17f67ab1fdb7a8-cgu.6.rcgu.o /target/debug/deps/paste-03c817d525241eb1.paste.7d17f67ab1fdb7a8-cgu.7.rcgu.o /target/debug/deps/rustcHYzDxd/rmeta.o /target/debug/deps/paste-03c817d525241eb1.drlfcgls4tmd2yug9nv0uklnt.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n21.161  rustc            1069741 1067201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hashbrown --edition=2024 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.17.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unused_extern_crates --warn=unsafe_op_in_unsafe_fn --warn=unreachable_pub --warn=clippy::str_to_string --warn=clippy::semicolon_if_nothing_returned --warn=clippy::ref_as_ptr ...\n"
    },
    {
      "argv": [
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1063415,
      "build_script_target_dir": "tree-sitter-language-04f523abf8aa8aa2",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build",
      "pid": 1063415,
      "ppid": 1063357,
      "root_cargo_pid": 1063357,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1063518,
      "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build-script-build",
      "pid": 1063518,
      "ppid": 1063357,
      "root_cargo_pid": 1063357,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-E",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/8236753969842890862detect_compiler_fami"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1063518,
      "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 1063519,
      "ppid": 1063518,
      "root_cargo_pid": 1063357,
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
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/8236753969842890862detect_compiler_fami",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-dumpbase",
        "8236753969842890862detect_compiler_family.c",
        "-dumpbase-ext",
        ".c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1063518,
      "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 1063520,
      "ppid": 1063519,
      "root_cargo_pid": 1063357,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1063518,
      "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 1063521,
      "ppid": 1063518,
      "root_cargo_pid": 1063357,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-E",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/5787956455649300018detect_compiler_fami"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1063518,
      "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 1063522,
      "ppid": 1063518,
      "root_cargo_pid": 1063357,
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
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/5787956455649300018detect_compiler_fami",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-dumpbase",
        "5787956455649300018detect_compiler_family.c",
        "-dumpbase-ext",
        ".c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1063518,
      "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 1063523,
      "ppid": 1063522,
      "root_cargo_pid": 1063357,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1063518,
      "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 1063524,
      "ppid": 1063518,
      "root_cargo_pid": 1063357,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-Wall",
        "-Wextra",
        "-Wno-unused-value",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/flag_check",
        "-c",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/flag_check.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1063518,
      "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 1063525,
      "ppid": 1063518,
      "root_cargo_pid": 1063357,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/flag_check.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/",
        "-dumpbase",
        "flag_check.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "-O0",
        "-Wall",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 1063518,
      "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 1063526,
      "ppid": 1063525,
      "root_cargo_pid": 1063357,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/flag_check",
        "/tmp/cc2YtBBh.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1063518,
      "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 1063527,
      "ppid": 1063525,
      "root_cargo_pid": 1063357,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-std=c11",
        "-I",
        "src",
        "-Wall",
        "-Wextra",
        "-Wno-unused-value",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-parser.o",
        "-c",
        "src/parser.c",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 1063518,
      "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 1063528,
      "ppid": 1063518,
      "root_cargo_pid": 1063357,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "src",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "src/parser.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/",
        "-dumpbase",
        "ea708c7824d36062-parser.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 1063518,
      "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 1063529,
      "ppid": 1063528,
      "root_cargo_pid": 1063357,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-I",
        "src",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-parser.o",
        "/tmp/cc2DdQzG.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1063518,
      "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 1064067,
      "ppid": 1063528,
      "root_cargo_pid": 1063357,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-std=c11",
        "-I",
        "src",
        "-Wall",
        "-Wextra",
        "-Wno-unused-value",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-scanner.o",
        "-c",
        "src/scanner.c",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 1063518,
      "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 1064068,
      "ppid": 1063518,
      "root_cargo_pid": 1063357,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "src",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "src/scanner.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/",
        "-dumpbase",
        "ea708c7824d36062-scanner.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 1063518,
      "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 1064069,
      "ppid": 1064068,
      "root_cargo_pid": 1063357,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-I",
        "src",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-scanner.o",
        "/tmp/cctYRJTb.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1063518,
      "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 1064070,
      "ppid": 1064068,
      "root_cargo_pid": 1063357,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-ar",
        "cqD",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/libtree-sitter-c-sharp.a",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-parser.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-scanner.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1063518,
      "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-ar",
      "pid": 1064071,
      "ppid": 1063518,
      "root_cargo_pid": 1063357,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-ar",
        "sD",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/libtree-sitter-c-sharp.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1063518,
      "build_script_target_dir": "tree-sitter-c-sharp-d38dba320c63e201",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-ar",
      "pid": 1064072,
      "ppid": 1063518,
      "root_cargo_pid": 1063357,
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
      "crate": "tree-sitter-c-sharp",
      "cwd": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "event_id": "bsrun:0e7f7ba30e356f07:25c8fc3cd2a08df6:6aca8841193a6edb",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
      "out_dir": "/target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
      "success": true,
      "target": null,
      "version": "0.23.1",
      "_owner": {
        "crate": "tree-sitter-c-sharp",
        "version": "0.23.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1#tree-sitter-c-sharp@0.23.1",
        "manifest_dir": "/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
  "item": {
    "rank": 4152,
    "crate": "tree-sitter-c-sharp",
    "version": "0.23.1",
    "crate_id": "306455",
    "version_id": "1335353",
    "downloads": 1947750,
    "cumulative_downloads": 110045587255,
    "cumulative_share_of_global": 0.4114350460826933,
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
