# `tree-sitter-java` `0.23.5`

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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
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
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
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
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-813428-1783997012595610398.map",
  "pid": 813428,
  "ppid": 813410,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-813428-1783997012595610398.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/libtree-sitter-java.a`

Owner: `tree-sitter-java` `0.23.5`

### Source files

* `/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5/src/parser.c`

### Source acquisition records

_None._

### Source preparation records

#### Record 1

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-std=c11",
    "-I",
    "src",
    "-Wall",
    "-Wextra",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/ea708c7824d36062-parser.o",
    "-c",
    "src/parser.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 813473,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 813480,
  "ppid": 813473,
  "root_cargo_pid": 813211,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_cwd_recovered_from_build_script_run": true
}
```

### Compilation records

#### Record 1

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "src",
    "-imultiarch",
    "aarch64-linux-gnu",
    "src/parser.c",
    "-quiet",
    "-dumpbase",
    "parser.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/ea708c7824d36062-parser.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c11",
    "..."
  ],
  "src": "src/parser.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/ea708c7824d36062-parser.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 813481,
  "ppid": 813480,
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "root_cargo_pid": 813211,
  "build_script_root_pid": 813473,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

### Archive records

#### Record 1

```json
{
  "event": "archive",
  "tool": "/usr/bin/aarch64-linux-gnu-ar",
  "real_tool": "/usr/bin/aarch64-linux-gnu-ar",
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cqD",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/libtree-sitter-java.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/ea708c7824d36062-parser.o"
  ],
  "archive": "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/libtree-sitter-java.a",
  "objects": [
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/ea708c7824d36062-parser.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 813521,
  "ppid": 813473,
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "root_cargo_pid": 813211,
  "build_script_root_pid": 813473,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
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
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "workspace_root": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5"
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
      "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
      "name": "tree-sitter-java",
      "version": "0.23.5",
      "manifest_path": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5"
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
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/raw-dylibs",
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
  "pid": 813235,
  "ppid": 813222,
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/raw-dylibs",
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
  "event_id": "used:cc:d9861ad91616b5cc:b853c32dd6e3a765:085e3bf50b18abef",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
  "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/symbols.o",
  "pid": 813235,
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/raw-dylibs",
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
  "pid": 813235,
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/raw-dylibs",
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
  "pid": 813235,
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/raw-dylibs",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/symbols.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/raw-dylibs",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/raw-dylibs",
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
  "context_path": "/tmp/native-trace-812382-1783997009446/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-812382-1783997009446/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 813235,
  "ppid": 813222,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/raw-dylibs",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG",
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
      "directory": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/symbols.o",
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
  "map_path": "/tmp/native-trace-link-cc-813235-1783997011790074593.map",
  "pid": 813235,
  "ppid": 813222,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-813235-1783997011790074593.map"
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "exit_code": 0,
  "kind": "exec",
  "pid": 813428,
  "ppid": 813410,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-java",
  "cargo_pkg_version": "0.23.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:2eda9b37ca3cbd17:2f859535e82ba34c:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
  "pid": 813428,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-java",
  "cargo_pkg_version": "0.23.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:2eda9b37ca3cbd17:8a3826dcd78120c3:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
  "pid": 813428,
  "sha256": "8b0677476d47d19f2c3a179a1abadbe2db693216473b846ff81e444209ef8e4a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-java",
  "cargo_pkg_version": "0.23.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:2eda9b37ca3cbd17:e1811f3e5cdf5c30:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
  "pid": 813428,
  "sha256": "625f841e3dbf6bd4879b2199e313e99419cb56a332d5bf38b421451cc32040b2",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-java",
  "cargo_pkg_version": "0.23.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:2eda9b37ca3cbd17:cdc230f618e7bbf3:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
  "pid": 813428,
  "sha256": "51677bfe9dc853d5acd1ceed987c3cd76d9c12d7f0298c596af5ac24586ae5f0",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-java",
  "cargo_pkg_version": "0.23.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:2eda9b37ca3cbd17:d60dfbbd24b0fded:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
  "pid": 813428,
  "sha256": "1eab3aee18d99524166cef01e8b94e0e54292dab1973b2c48a4a498cd5bfce71",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-java",
  "cargo_pkg_version": "0.23.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:2eda9b37ca3cbd17:4a6595aefdde1ead:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
  "pid": 813428,
  "sha256": "2e2cf0c398e8643e5b308e44a0c336ba6043c6ad94d77e6bbc372afe299ddead",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-java",
  "cargo_pkg_version": "0.23.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:2eda9b37ca3cbd17:a6f6f1fc9d2c0ccb:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
  "pid": 813428,
  "sha256": "b6db58fba3dc506c3e9c26880ca45e545cb90de1fef48f37a0894d06b875b83d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-java",
  "cargo_pkg_version": "0.23.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:2eda9b37ca3cbd17:33fb1384e47def29:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
  "pid": 813428,
  "sha256": "ae8b8ba805dcdc14ea2148e37a7c583571915503caf65dbdec0421894ca5ffe0",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-java",
  "cargo_pkg_version": "0.23.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:2eda9b37ca3cbd17:1797e576e7c13738:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
  "pid": 813428,
  "sha256": "4d5332eadcab27c1d65f056aeabc64ba1a9bc26262a1d9d0e41b1653366cdc9b",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-java",
  "cargo_pkg_version": "0.23.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:2eda9b37ca3cbd17:a1d79aeade99e814:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
  "pid": 813428,
  "sha256": "08295a2627cde7d9d4e33f7f3bb435f58f6f96b453ad0c02d92d2ded687d591c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-java",
  "cargo_pkg_version": "0.23.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:2eda9b37ca3cbd17:39ee2940d8abec22:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
  "pid": 813428,
  "sha256": "23af8845d11eba8b868c472048338a7394792d986164dffea633430beb5dfefe",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-java",
  "cargo_pkg_version": "0.23.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:2eda9b37ca3cbd17:64d85060a6a8bfda:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
  "pid": 813428,
  "sha256": "5f89de638decc160442662d19c142755a65cf8a2a8ab3cb9ede17a54a107273e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-java",
  "cargo_pkg_version": "0.23.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:2eda9b37ca3cbd17:9b7a98dc152883e5:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
  "pid": 813428,
  "sha256": "75468453c13ef230dac3751b703b1015b0a13f788d7cdd74029370ef9cdb8fcd",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
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
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "cargo_pkg_name": "tree-sitter-java",
  "cargo_pkg_version": "0.23.5",
  "context_path": "/tmp/native-trace-812382-1783997009446/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-812382-1783997009446/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 813428,
  "ppid": 813410,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
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
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-813428-1783997012595610398.map",
  "pid": 813428,
  "ppid": 813410,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-813428-1783997012595610398.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
  "parsed_event_count": 320,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 321,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "ame cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n8.947   cc               814194 814165   0 /tmp/native-trace-814056-1783997018538/shims/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcN3QRoi/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n8.948   cc               814195 814194   0 /usr/bin/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcN3QRoi/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n8.951   collect2         814196 814195   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgEkslM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n8.952   ld.lld           814197 814196   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgEkslM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db ...\n8.954   rust-lld         814197 814196   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgEkslM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n8.996   build-script-bu  814215 814155   0 /target/debug/build/libc-8a22300c8f78b6db/build-script-build\n8.998   rustc            814216 814215   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n9.010   rustc            814220 814155   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n9.013   cargo            814221 814143   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n9.025   rustc            814225 814221   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n9.044   rustc            814233 814221   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n9.044   rustc            814235 814221   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n9.044   rustc            814234 814221   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name find_msvc_tools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n9.089   cc               814248 814235   0 /tmp/native-trace-814143-1783997018737/shims/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n9.090   cc               814249 814248   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n9.093   collect2         814250 814249   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgOKxfV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.094   ld.lld           814251 814250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgOKxfV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2 ...\n9.096   rust-lld         814251 814250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgOKxfV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.117   rustc            814274 814221   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n9.141   build-script-bu  814280 814221   0 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build\n9.145   rustc            814282 814221   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_language --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/src/language.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n9.562   rustc            814314 814155   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=06b7662075ecae39 ...\n9.601   cc               814330 814314   0 /tmp/native-trace-814056-1783997018538/shims/cc -m64 /target/debug/build/file-lock-e7ec189e8a3c419e/rustcwtfTDy/symbols.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.3c3psple0gmv7yyyqbp3fgtcd.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.401d3kyjceojcgroawg6c9nf0.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.56ucri67nlogpucsi59dqr1hc.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.8cjtzgjhebof5tgf3ur55jtke.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.9mq8ou3x1tjs9nkpxzempsbhb.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.bm7tz27hlft2omjdgnf6azk3u.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.c7qrznfrt7tj7vr46f9y3pxbi.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.e4wu78s2munsd8k0hgjdupuy7.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.71a4npaby13yh9u2xmrbik0dn.12g3pyy.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n9.602   cc               814332 814330   0 /usr/bin/cc -m64 /target/debug/build/file-lock-e7ec189e8a3c419e/rustcwtfTDy/symbols.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.3c3psple0gmv7yyyqbp3fgtcd.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.401d3kyjceojcgroawg6c9nf0.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.56ucri67nlogpucsi59dqr1hc.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.8cjtzgjhebof5tgf3ur55jtke.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.9mq8ou3x1tjs9nkpxzempsbhb.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.bm7tz27hlft2omjdgnf6azk3u.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.c7qrznfrt7tj7vr46f9y3pxbi.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.e4wu78s2munsd8k0hgjdupuy7.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.71a4npaby13yh9u2xmrbik0dn.12g3pyy.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n9.604   collect2         814333 814332   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc11LcKb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.605   ld.lld           814334 814333   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc11LcKb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e ...\n9.606   rust-lld         814334 814333   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc11LcKb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.675   build-script-bu  814359 814155   0 /target/debug/build/file-lock-e7ec189e8a3c419e/build-script-build\n9.676   aarch64-linux-g  814360 814359   0 /usr/bin/aarch64-linux-gnu-gcc -E /target/aarch64-unknown-linux-gnu/debug/build/file-lock-f6b94f5e5d1894a8/out/949125479893546352detect_compiler_family.c\n9.678   cc1              814361 814360   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/file-lock-f6b94f5e5d1894a8/out/949125479893546352detect_compiler_family.c -mlittle-endian -mabi=lp64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n9.683   aarch64-linux-g  814363 814359   0 /usr/bin/aarch64-linux-gnu-gcc -?\n9.686   aarch64-linux-g  814364 814359   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/file-lock-f6b94f5e5d1894a8/out/ea708c7824d36062-file_lock.o -c src/file_lock.c\n9.687   cc1              814365 814364   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu src/file_lock.c -quiet -dumpbase file_lock.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/file-lock-f6b94f5e5d1894a8/out/ea708c7824d36062-file_lock.o -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC ...\n9.703   as               814368 814364   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/file-lock-f6b94f5e5d1894a8/out/ea708c7824d36062-file_lock.o /tmp/cc2bZQnz.s\n9.713   aarch64-linux-g  814370 814359   0 /usr/bin/aarch64-linux-gnu-ar cqD /target/aarch64-unknown-linux-gnu/debug/build/file-lock-f6b94f5e5d1894a8/out/libfile_lock.a /target/aarch64-unknown-linux-gnu/debug/build/file-lock-f6b94f5e5d1894a8/out/ea708c7824d36062-file_lock.o\n9.716   aarch64-linux-g  814371 814359   0 /usr/bin/aarch64-linux-gnu-ar sD /target/aarch64-unknown-linux-gnu/debug/build/file-lock-f6b94f5e5d1894a8/out/libfile_lock.a\n9.721   rustc            814373 814155   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name file_lock --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=33723ec93a77dd2f ...\n9.773   rustc            814396 814221   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 bindings/rust/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=325df26c51708d57 ...\n9.814   cc               814413 814396   0 /tmp/native-trace-814143-1783997018737/shims/cc -m64 /target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n9.814   cc               814414 814413   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n9.817   collect2         814415 814414   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxRIvXm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.819   ld.lld           814416 814415   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxRIvXm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082 ...\n9.820   rust-lld         814416 814415   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxRIvXm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.882   build-script-bu  814434 814221   0 /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build-script-build\n9.883   powerpc64le-lin  814435 814434   0 /usr/bin/powerpc64le-linux-gnu-gcc -E /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/13831713749963907173detect_compiler_fami\n9.884   cc1              814436 814435   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -imultiarch powerpc64le-linux-gnu /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/13831713749963907173detect_compiler_fami -msecure-plt -mcpu=power8 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n9.889   powerpc64le-lin  814437 814434   0 /usr/bin/powerpc64le-linux-gnu-gcc -?\n9.892   powerpc64le-lin  814438 814434   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I src -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o -c src/parser.c\n9.893   cc1              814439 814438   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I src -imultiarch powerpc64le-linux-gnu src/parser.c -msecure-plt -quiet -dumpbase parser.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o -g -gdwarf-4 -O0 -Wall -Wextra ...\n10.087  as               814440 814438   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I src -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o /tmp/ccsrdoca.s\n10.093  runc             814442 810767   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3b46886501ccd7fcca6ba4ca379e3386839ba0c23f262bf08939523b67c --log-format json --systemd-cgroup kill --all 3b46886501ccd7fcca6ba4ca379e3386839ba0c23f262bf08939523b67cf96a6 9\n10.109  runc             814448 810767   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3b46886501ccd7fcca6ba4ca379e3386839ba0c23f262bf08939523b67c --log-format json --systemd-cgroup delete 3b46886501ccd7fcca6ba4ca379e3386839ba0c23f262bf08939523b67cf96a6\n10.115  powerpc64le-lin  814454 814434   0 /usr/bin/powerpc64le-linux-gnu-ar cqD /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/libtree-sitter-java.a /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o\n10.118  powerpc64le-lin  814455 814434   0 /usr/bin/powerpc64le-linux-gnu-ar sD /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/libtree-sitter-java.a\n10.124  rustc            814457 814221   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_java --edition=2021 bindings/rust/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=456ee8e8757d3710 ...\n10.162  runc             814465 810582   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/87837031b3add06156ac511ff5193387979842194bdb3bc2194361fac45 --log-format json --systemd-cgroup kill --all 87837031b3add06156ac511ff5193387979842194bdb3bc2194361fac451c8d5 9\n10.179  runc             814471 810582   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/87837031b3add06156ac511ff5193387979842194bdb3bc2194361fac45 --log-format json --systemd-cgroup delete 87837031b3add06156ac511ff5193387979842194bdb3bc2194361fac451c8d5\n10.321  containerd-shim  814478 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 3b46886501ccd7fcca6ba4ca379e3386839ba0c23f262bf08939523b67cf96a6 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3b46886501ccd7fcca6ba4ca379e3386839ba0c23f262bf08939523b67c delete\n10.323  runc             814485 814478   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3b46886501ccd7fcca6ba4ca379e3386839ba0c23f262bf08939523b67cf96a --log-format json delete --force 3b46886501ccd7fcca6ba4ca379e3386839ba0c23f262bf08939523b67cf96a6\n10.371  sh               814493 814490   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth6db6322\n10.372  ethtool          814494 814493   0 /usr/sbin/ethtool -i veth6db6322\n10.372  sed              814495 814493   0 /usr/bin/sed -n s/^driver: //p\n10.378  systemd-sysctl   814499 814490   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth6db6322 --prefix=/net/ipv4/neigh/veth6db6322 --prefix=/net/ipv6/conf/veth6db6322 --prefix=/net/ipv6/neigh/veth6db6322\n10.476  containerd-shim  814501 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 87837031b3add06156ac511ff5193387979842194bdb3bc2194361fac451c8d5 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/87837031b3add06156ac511ff5193387979842194bdb3bc2194361fac45 delete\n10.479  runc             814508 814501   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/87837031b3add06156ac511ff5193387979842194bdb3bc2194361fac451c8d --log-format json delete --force 87837031b3add06156ac511ff5193387979842194bdb3bc2194361fac451c8d5\n10.514  systemd-sysctl   814513 814490   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2b80805 --prefix=/net/ipv4/neigh/veth2b80805 --prefix=/net/ipv6/conf/veth2b80805 --prefix=/net/ipv6/neigh/veth2b80805\n11.604  cross            814515 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n11.605  rustc            814518 814515   0 /home/xmoe/.cargo/bin/rustc --print target-list\n11.612  rustc            814518 814515   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n11.626  rustc            814530 814515   0 /home/xmoe/.cargo/bin/rustc -vV\n11.632  rustc            814530 814515   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n11.644  cargo            814540 814515   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n11.651  cargo            814540 814515   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n11.664  rustc            814549 814540   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n11.675  rustc            814551 814540   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n11.689  rustc            814555 814540   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n11.823  rustc            814560 814540   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n11.846  rustc            814562 814515   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n11.854  rustc            814562 814515   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n11.868  docker           814574 814515   0 /usr/bin/docker --help\n11.884  docker           814585 814515   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n11.898  runc             814595 1599     0 /usr/bin/runc --version\n11.901  docker-init      814601 1599     0 /usr/bin/docker-init --version\n11.903  docker           814602 814515   0 /usr/bin/docker info -f {{.SecurityOptions}}\n11.916  runc             814613 1599     0 /usr/bin/runc --version\n11.920  docker-init      814619 1599     0 /usr/bin/docker-init --version\n11.945  rustup           814620 814515   0 /home/xmoe/.cargo/bin/rustup toolchain list\n11.953  rustup           814629 814515   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n11.983  rustup           814638 814515   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n12.010  uname            814647 814515   0 /usr/bin/uname -r\n12.024  docker           814648 814515   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n12.058  systemd-sysctl   814661 814490   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethdc4b4d4 --prefix=/net/ipv4/neigh/vethdc4b4d4 --prefix=/net/ipv6/conf/vethdc4b4d4 --prefix=/net/ipv6/neigh/vethdc4b4d4\n12.058  systemd-sysctl   814662 814514   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb599a89 --prefix=/net/ipv4/neigh/vethb599a89 --prefix=/net/ipv6/conf/vethb599a89 --prefix=/net/ipv6/neigh/vethb599a89\n12.072  containerd-shim  814693 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 5fe98d9bcf5cacd10b943b6646b1a66cd198c16423f088dfff5d30ff2ff35d07 start\n12.075  containerd-shim  814700 814693   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 5fe98d9bcf5cacd10b943b6646b1a66cd198c16423f088dfff5d30ff2ff35d07 -address /var/run/docker/containerd/containerd.sock\n12.079  runc             814710 814700   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5fe98d9bcf5cacd10b943b6646b1a66cd198c16423f088dfff5d30ff2ff --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5fe98d9bcf5cacd10b943b6646b1a66cd198c16423f088dfff5d30ff2ff --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5fe98d9bcf5cacd10b943b6646b1a66cd198c16423f088dfff5d30ff2ff 5fe98d9bcf5cacd10b943b6646b1a66cd198c16423f088dfff5d30ff2ff35d07\n12.083  exe              814717 814710   0 /proc/self/exe init\n12.116  exe              814727 814710   0 /proc/1599/exe -exec-root=/var/run/docker 5fe98d9bcf5cacd10b943b6646b1a66cd198c16423f088dfff5d30ff2ff35d07 d7da31e8f8e1\n12.135  exe              814734 1599     0 /proc/self/exe /var/run/docker/netns/cd87fd8fb70d all false\n12.181  runc             814753 814700   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5fe98d9bcf5cacd10b943b6646b1a66cd198c16423f088dfff5d30ff2ff --log-format json --systemd-cgroup start 5fe98d9bcf5cacd10b943b6646b1a66cd198c16423f088dfff5d30ff2ff35d07\n12.186  sh               814721 814700   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n12.186  cargo            814759 814721   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n12.196  cargo-native-tr  814759 814721   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n12.199  cargo            814760 814759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n12.210  rustc            814761 814760   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n12.222  rustc            814763 814760   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n12.240  execsnoop        814767 814759   0 /usr/local/bin/execsnoop -t\n12.241  python3          814767 814759   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n12.369  runc             814770 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process4142851923 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n12.374  exe              814777 814770   0 /proc/self/exe init\n12.399  etcdctl          814780 814770   0 /usr/local/bin/etcdctl endpoint health\n13.036  16               814795 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n13.054  frpc             814795 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n14.183  cargo            814801 814759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n14.195  rustc            814802 814801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n14.215  rustc            814810 814801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name find_msvc_tools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n14.215  rustc            814811 814801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n14.216  rustc            814812 814801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n14.276  rustc            814830 814801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n14.331  cc               814840 814812   0 /tmp/native-trace-814759-1783997023809/shims/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcD14q7p/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n14.332  cc               814841 814840   0 /usr/bin/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcD14q7p/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n14.334  collect2         814842 814841   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBhLJSG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n14.336  ld.lld           814843 814842   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBhLJSG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db ...\n14.336  rust-lld         814843 814842   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBhLJSG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n14.376  build-script-bu  814861 814801   0 /target/debug/build/libc-8a22300c8f78b6db/build-script-build\n14.377  rustc            814862 814861   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n14.389  rustc            814866 814801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n14.881  rustc            814892 814801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=06b7662075ecae39 ...\n14.915  cc               814906 814892   0 /tmp/native-trace-814759-1783997023809/shims/cc -m64 /target/debug/build/file-lock-e7ec189e8a3c419e/rustcamM1WB/symbols.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.3c3psple0gmv7yyyqbp3fgtcd.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.401d3kyjceojcgroawg6c9nf0.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.56ucri67nlogpucsi59dqr1hc.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.8cjtzgjhebof5tgf3ur55jtke.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.9mq8ou3x1tjs9nkpxzempsbhb.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.bm7tz27hlft2omjdgnf6azk3u.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.c7qrznfrt7tj7vr46f9y3pxbi.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.e4wu78s2munsd8k0hgjdupuy7.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.71a4npaby13yh9u2xmrbik0dn.0fbramd.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n14.916  cc               814907 814906   0 /usr/bin/cc -m64 /target/debug/build/file-lock-e7ec189e8a3c419e/rustcamM1WB/symbols.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.3c3psple0gmv7yyyqbp3fgtcd.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.401d3kyjceojcgroawg6c9nf0.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.56ucri67nlogpucsi59dqr1hc.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.8cjtzgjhebof5tgf3ur55jtke.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.9mq8ou3x1tjs9nkpxzempsbhb.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.bm7tz27hlft2omjdgnf6azk3u.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.c7qrznfrt7tj7vr46f9y3pxbi.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.e4wu78s2munsd8k0hgjdupuy7.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.71a4npaby13yh9u2xmrbik0dn.0fbramd.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n14.918  collect2         814908 814907   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc4HdQe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n14.919  ld.lld           814909 814908   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc4HdQe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e ...\n14.920  rust-lld         814909 814908   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc4HdQe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n14.974  build-script-bu  814927 814801   0 /target/debug/build/file-lock-e7ec189e8a3c419e/build-script-build\n14.975  riscv64-linux-g  814928 814927   0 /usr/bin/riscv64-linux-gnu-gcc -E /target/riscv64gc-unknown-linux-gnu/debug/build/file-lock-7682ed3b3f968295/out/4518273080423325231detect_compiler_family.c\n14.976  cc1              814929 814928   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/file-lock-7682ed3b3f968295/out/4518273080423325231detect_compiler_family.c -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -fstack-protector-strong -Wformat -Wformat-security -dumpbase 4518273080423325231detect_compiler_family.c -dumpbase-ext .c\n14.981  riscv64-linux-g  814930 814927   0 /usr/bin/riscv64-linux-gnu-gcc -?\n14.984  riscv64-linux-g  814931 814927   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/file-lock-7682ed3b3f968295/out/ea708c7824d36062-file_lock.o -c src/file_lock.c\n14.985  cc1              814932 814931   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu src/file_lock.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/file-lock-7682ed3b3f968295/out/ -dumpbase ea708c7824d36062-file_lock.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g -gdwarf-4 ...\n14.997  as               814933 814931   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/file-lock-7682ed3b3f968295/out/ea708c7824d36062-file_lock.o /tmp/ccUEbCuy.s\n14.999  riscv64-linux-g  814934 814927   0 /usr/bin/riscv64-linux-gnu-ar cqD /target/riscv64gc-unknown-linux-gnu/debug/build/file-lock-7682ed3b3f968295/out/libfile_lock.a /target/riscv64gc-unknown-linux-gnu/debug/build/file-lock-7682ed3b3f968295/out/ea708c7824d36062-file_lock.o\n15.015  riscv64-linux-g  814935 814927   0 /usr/bin/riscv64-linux-gnu-ar sD /target/riscv64gc-unknown-linux-gnu/debug/build/file-lock-7682ed3b3f968295/out/libfile_lock.a\n15.034  rustc            814937 814801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name file_lock --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=80fcdc70949e12f0 ...\n17.191  runc             814957 811662   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4fd8cd13e6fe4cd3bbbd1d1c3e6ae2ed357f3b762c8f19a46dd198093ec --log-format json --systemd-cgroup kill --all 4fd8cd13e6fe4cd3bbbd1d1c3e6ae2ed357f3b762c8f19a46dd198093ec69bfc 9\n17.210  runc             814964 811662   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4fd8cd13e6fe4cd3bbbd1d1c3e6ae2ed357f3b762c8f19a46dd198093ec --log-format json --systemd-cgroup delete 4fd8cd13e6fe4cd3bbbd1d1c3e6ae2ed357f3b762c8f19a46dd198093ec69bfc\n17.377  containerd-shim  814970 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 4fd8cd13e6fe4cd3bbbd1d1c3e6ae2ed357f3b762c8f19a46dd198093ec69bfc -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4fd8cd13e6fe4cd3bbbd1d1c3e6ae2ed357f3b762c8f19a46dd198093ec delete\n17.380  runc             814976 814970   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4fd8cd13e6fe4cd3bbbd1d1c3e6ae2ed357f3b762c8f19a46dd198093ec69bf --log-format json delete --force 4fd8cd13e6fe4cd3bbbd1d1c3e6ae2ed357f3b762c8f19a46dd198093ec69bfc\n17.426  systemd-sysctl   814983 814982   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe83f654 --prefix=/net/ipv4/neigh/vethe83f654 --prefix=/net/ipv6/conf/vethe83f654 --prefix=/net/ipv6/neigh/vethe83f654\n17.553  runc             814985 811685   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3e28ab9136f3f75a4852e40d8b9d77b153275104a4e3d926d76c36d9936 --log-format json --systemd-cgroup kill --all 3e28ab9136f3f75a4852e40d8b9d77b153275104a4e3d926d76c36d9936c39a4 9\n17.561  runc             814992 811685   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3e28ab9136f3f75a4852e40d8b9d77b153275104a4e3d926d76c36d9936 --log-format json --systemd-cgroup delete 3e28ab9136f3f75a4852e40d8b9d77b153275104a4e3d926d76c36d9936c39a4\n17.767  containerd-shim  814998 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 3e28ab9136f3f75a4852e40d8b9d77b153275104a4e3d926d76c36d9936c39a4 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3e28ab9136f3f75a4852e40d8b9d77b153275104a4e3d926d76c36d9936 delete\n17.770  runc             815004 814998   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3e28ab9136f3f75a4852e40d8b9d77b153275104a4e3d926d76c36d9936c39a --log-format json delete --force 3e28ab9136f3f75a4852e40d8b9d77b153275104a4e3d926d76c36d9936c39a4\n17.807  runc             815011 811663   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/86de489dd7ba965d8738fb3dfd51ebc7644fad87286066b04f9738e5485 --log-format json --systemd-cgroup kill --all 86de489dd7ba965d8738fb3dfd51ebc7644fad87286066b04f9738e548503529 9\n17.814  systemd-sysctl   815017 814982   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth6616e51 --prefix=/net/ipv4/neigh/veth6616e51 --prefix=/net/ipv6/conf/veth6616e51 --prefix=/net/ipv6/neigh/veth6616e51\n17.815  runc             815018 811663   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/86de489dd7ba965d8738fb3dfd51ebc7644fad87286066b04f9738e5485 --log-format json --systemd-cgroup delete 86de489dd7ba965d8738fb3dfd51ebc7644fad87286066b04f9738e548503529\n17.988  containerd-shim  815025 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 86de489dd7ba965d8738fb3dfd51ebc7644fad87286066b04f9738e548503529 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/86de489dd7ba965d8738fb3dfd51ebc7644fad87286066b04f9738e5485 delete\n17.991  runc             815032 815025   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/86de489dd7ba965d8738fb3dfd51ebc7644fad87286066b04f9738e54850352 --log-format json delete --force 86de489dd7ba965d8738fb3dfd51ebc7644fad87286066b04f9738e548503529\n18.031  systemd-sysctl   815037 814982   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth005461e --prefix=/net/ipv4/neigh/veth005461e --prefix=/net/ipv6/conf/veth005461e --prefix=/net/ipv6/neigh/veth005461e\n"
}
```

#### Record 28

```json
{
  "argv": [
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 813266,
  "build_script_target_dir": "tree-sitter-language-04f523abf8aa8aa2",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build",
  "pid": 813266,
  "ppid": 813211,
  "root_cargo_pid": 813211,
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 813473,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build-script-build",
  "pid": 813473,
  "ppid": 813211,
  "root_cargo_pid": 813211,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out"
}
```

#### Record 30

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-E",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/4954000664577432107detect_compiler_family.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 813473,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 813475,
  "ppid": 813473,
  "root_cargo_pid": 813211,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 31

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-quiet",
    "-imultiarch",
    "aarch64-linux-gnu",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/4954000664577432107detect_compiler_family.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 813473,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 813476,
  "ppid": 813475,
  "root_cargo_pid": 813211,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 32

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 813473,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 813479,
  "ppid": 813473,
  "root_cargo_pid": 813211,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 33

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-std=c11",
    "-I",
    "src",
    "-Wall",
    "-Wextra",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/ea708c7824d36062-parser.o",
    "-c",
    "src/parser.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 813473,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 813480,
  "ppid": 813473,
  "root_cargo_pid": 813211,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 34

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "src",
    "-imultiarch",
    "aarch64-linux-gnu",
    "src/parser.c",
    "-quiet",
    "-dumpbase",
    "parser.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/ea708c7824d36062-parser.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c11",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 813473,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 813481,
  "ppid": 813480,
  "root_cargo_pid": 813211,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 35

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-I",
    "src",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/ea708c7824d36062-parser.o",
    "/tmp/ccpXze2J.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 813473,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 813520,
  "ppid": 813480,
  "root_cargo_pid": 813211,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 36

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cqD",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/libtree-sitter-java.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/ea708c7824d36062-parser.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 813473,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 813521,
  "ppid": 813473,
  "root_cargo_pid": 813211,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 37

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "sD",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/libtree-sitter-java.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 813473,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 813522,
  "ppid": 813473,
  "root_cargo_pid": 813211,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 38

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

#### Record 39

```json
{
  "crate": "tree-sitter-java",
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "event_id": "bsrun:076a9138da0c3f07:5b4e52ebebf54619:416f8f7a19a7071a",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
  "success": true,
  "target": null,
  "version": "0.23.5",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  }
}
```

#### Record 40

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "src",
    "-imultiarch",
    "aarch64-linux-gnu",
    "src/parser.c",
    "-quiet",
    "-dumpbase",
    "parser.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/ea708c7824d36062-parser.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c11",
    "..."
  ],
  "src": "src/parser.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/ea708c7824d36062-parser.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 813481,
  "ppid": 813480,
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "root_cargo_pid": 813211,
  "build_script_root_pid": 813473,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 41

```json
{
  "event": "archive",
  "tool": "/usr/bin/aarch64-linux-gnu-ar",
  "real_tool": "/usr/bin/aarch64-linux-gnu-ar",
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cqD",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/libtree-sitter-java.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/ea708c7824d36062-parser.o"
  ],
  "archive": "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/libtree-sitter-java.a",
  "objects": [
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/ea708c7824d36062-parser.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 813521,
  "ppid": 813473,
  "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "root_cargo_pid": 813211,
  "build_script_root_pid": 813473,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T02:43:55.289847+00:00",
  "crate": "tree-sitter-java",
  "version": "0.23.5",
  "architecture": "aarch64",
  "duration_seconds": 30.433151870034635,
  "trace_record_count": 39,
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
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
        "manifest_path": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5/Cargo.toml"
      }
    ],
    "attributed_event_count": 27,
    "unattributed_event_count": 12,
    "owners": [
      {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
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
      "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "workspace_root": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5"
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
          "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
          "name": "tree-sitter-java",
          "version": "0.23.5",
          "manifest_path": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5"
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
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/raw-dylibs",
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
      "pid": 813235,
      "ppid": 813222,
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/raw-dylibs",
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
      "event_id": "used:cc:d9861ad91616b5cc:b853c32dd6e3a765:085e3bf50b18abef",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
      "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/symbols.o",
      "pid": 813235,
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/raw-dylibs",
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
      "pid": 813235,
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/raw-dylibs",
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
      "pid": 813235,
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/raw-dylibs",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/symbols.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/raw-dylibs",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/raw-dylibs",
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
      "context_path": "/tmp/native-trace-812382-1783997009446/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-812382-1783997009446/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 813235,
      "ppid": 813222,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/raw-dylibs",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG",
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
          "directory": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcSQBcQG/symbols.o",
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
      "map_path": "/tmp/native-trace-link-cc-813235-1783997011790074593.map",
      "pid": 813235,
      "ppid": 813222,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-813235-1783997011790074593.map"
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "exit_code": 0,
      "kind": "exec",
      "pid": 813428,
      "ppid": 813410,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-java",
      "cargo_pkg_version": "0.23.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:2eda9b37ca3cbd17:2f859535e82ba34c:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
      "pid": 813428,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-java",
      "cargo_pkg_version": "0.23.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:2eda9b37ca3cbd17:8a3826dcd78120c3:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
      "pid": 813428,
      "sha256": "8b0677476d47d19f2c3a179a1abadbe2db693216473b846ff81e444209ef8e4a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-java",
      "cargo_pkg_version": "0.23.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:2eda9b37ca3cbd17:e1811f3e5cdf5c30:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
      "pid": 813428,
      "sha256": "625f841e3dbf6bd4879b2199e313e99419cb56a332d5bf38b421451cc32040b2",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-java",
      "cargo_pkg_version": "0.23.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:2eda9b37ca3cbd17:cdc230f618e7bbf3:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
      "pid": 813428,
      "sha256": "51677bfe9dc853d5acd1ceed987c3cd76d9c12d7f0298c596af5ac24586ae5f0",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-java",
      "cargo_pkg_version": "0.23.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:2eda9b37ca3cbd17:d60dfbbd24b0fded:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
      "pid": 813428,
      "sha256": "1eab3aee18d99524166cef01e8b94e0e54292dab1973b2c48a4a498cd5bfce71",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-java",
      "cargo_pkg_version": "0.23.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:2eda9b37ca3cbd17:4a6595aefdde1ead:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
      "pid": 813428,
      "sha256": "2e2cf0c398e8643e5b308e44a0c336ba6043c6ad94d77e6bbc372afe299ddead",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-java",
      "cargo_pkg_version": "0.23.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:2eda9b37ca3cbd17:a6f6f1fc9d2c0ccb:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
      "pid": 813428,
      "sha256": "b6db58fba3dc506c3e9c26880ca45e545cb90de1fef48f37a0894d06b875b83d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-java",
      "cargo_pkg_version": "0.23.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:2eda9b37ca3cbd17:33fb1384e47def29:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
      "pid": 813428,
      "sha256": "ae8b8ba805dcdc14ea2148e37a7c583571915503caf65dbdec0421894ca5ffe0",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-java",
      "cargo_pkg_version": "0.23.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:2eda9b37ca3cbd17:1797e576e7c13738:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
      "pid": 813428,
      "sha256": "4d5332eadcab27c1d65f056aeabc64ba1a9bc26262a1d9d0e41b1653366cdc9b",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-java",
      "cargo_pkg_version": "0.23.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:2eda9b37ca3cbd17:a1d79aeade99e814:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
      "pid": 813428,
      "sha256": "08295a2627cde7d9d4e33f7f3bb435f58f6f96b453ad0c02d92d2ded687d591c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-java",
      "cargo_pkg_version": "0.23.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:2eda9b37ca3cbd17:39ee2940d8abec22:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
      "pid": 813428,
      "sha256": "23af8845d11eba8b868c472048338a7394792d986164dffea633430beb5dfefe",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-java",
      "cargo_pkg_version": "0.23.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:2eda9b37ca3cbd17:64d85060a6a8bfda:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
      "pid": 813428,
      "sha256": "5f89de638decc160442662d19c142755a65cf8a2a8ab3cb9ede17a54a107273e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-java",
      "cargo_pkg_version": "0.23.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:2eda9b37ca3cbd17:9b7a98dc152883e5:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
      "pid": 813428,
      "sha256": "75468453c13ef230dac3751b703b1015b0a13f788d7cdd74029370ef9cdb8fcd",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
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
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "cargo_pkg_name": "tree-sitter-java",
      "cargo_pkg_version": "0.23.5",
      "context_path": "/tmp/native-trace-812382-1783997009446/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-812382-1783997009446/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 813428,
      "ppid": 813410,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
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
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustcLyXXzR/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.1edf5rm.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.1edf5rm.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.1edf5rm.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.1edf5rm.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.1edf5rm.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.1edf5rm.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.1edf5rm.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.1edf5rm.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.1edf5rm.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.1edf5rm.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.1edf5rm.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.1edf5rm.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-813428-1783997012595610398.map",
      "pid": 813428,
      "ppid": 813410,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-813428-1783997012595610398.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
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
      "parsed_event_count": 320,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 321,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "ame cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n8.947   cc               814194 814165   0 /tmp/native-trace-814056-1783997018538/shims/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcN3QRoi/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n8.948   cc               814195 814194   0 /usr/bin/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcN3QRoi/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n8.951   collect2         814196 814195   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgEkslM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n8.952   ld.lld           814197 814196   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgEkslM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db ...\n8.954   rust-lld         814197 814196   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgEkslM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n8.996   build-script-bu  814215 814155   0 /target/debug/build/libc-8a22300c8f78b6db/build-script-build\n8.998   rustc            814216 814215   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n9.010   rustc            814220 814155   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n9.013   cargo            814221 814143   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n9.025   rustc            814225 814221   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n9.044   rustc            814233 814221   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n9.044   rustc            814235 814221   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n9.044   rustc            814234 814221   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name find_msvc_tools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n9.089   cc               814248 814235   0 /tmp/native-trace-814143-1783997018737/shims/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n9.090   cc               814249 814248   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n9.093   collect2         814250 814249   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgOKxfV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.094   ld.lld           814251 814250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgOKxfV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2 ...\n9.096   rust-lld         814251 814250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgOKxfV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.117   rustc            814274 814221   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n9.141   build-script-bu  814280 814221   0 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build\n9.145   rustc            814282 814221   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_language --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/src/language.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n9.562   rustc            814314 814155   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=06b7662075ecae39 ...\n9.601   cc               814330 814314   0 /tmp/native-trace-814056-1783997018538/shims/cc -m64 /target/debug/build/file-lock-e7ec189e8a3c419e/rustcwtfTDy/symbols.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.3c3psple0gmv7yyyqbp3fgtcd.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.401d3kyjceojcgroawg6c9nf0.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.56ucri67nlogpucsi59dqr1hc.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.8cjtzgjhebof5tgf3ur55jtke.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.9mq8ou3x1tjs9nkpxzempsbhb.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.bm7tz27hlft2omjdgnf6azk3u.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.c7qrznfrt7tj7vr46f9y3pxbi.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.e4wu78s2munsd8k0hgjdupuy7.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.71a4npaby13yh9u2xmrbik0dn.12g3pyy.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n9.602   cc               814332 814330   0 /usr/bin/cc -m64 /target/debug/build/file-lock-e7ec189e8a3c419e/rustcwtfTDy/symbols.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.3c3psple0gmv7yyyqbp3fgtcd.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.401d3kyjceojcgroawg6c9nf0.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.56ucri67nlogpucsi59dqr1hc.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.8cjtzgjhebof5tgf3ur55jtke.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.9mq8ou3x1tjs9nkpxzempsbhb.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.bm7tz27hlft2omjdgnf6azk3u.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.c7qrznfrt7tj7vr46f9y3pxbi.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.e4wu78s2munsd8k0hgjdupuy7.12g3pyy.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.71a4npaby13yh9u2xmrbik0dn.12g3pyy.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n9.604   collect2         814333 814332   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc11LcKb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.605   ld.lld           814334 814333   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc11LcKb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e ...\n9.606   rust-lld         814334 814333   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc11LcKb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.675   build-script-bu  814359 814155   0 /target/debug/build/file-lock-e7ec189e8a3c419e/build-script-build\n9.676   aarch64-linux-g  814360 814359   0 /usr/bin/aarch64-linux-gnu-gcc -E /target/aarch64-unknown-linux-gnu/debug/build/file-lock-f6b94f5e5d1894a8/out/949125479893546352detect_compiler_family.c\n9.678   cc1              814361 814360   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/file-lock-f6b94f5e5d1894a8/out/949125479893546352detect_compiler_family.c -mlittle-endian -mabi=lp64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n9.683   aarch64-linux-g  814363 814359   0 /usr/bin/aarch64-linux-gnu-gcc -?\n9.686   aarch64-linux-g  814364 814359   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/file-lock-f6b94f5e5d1894a8/out/ea708c7824d36062-file_lock.o -c src/file_lock.c\n9.687   cc1              814365 814364   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu src/file_lock.c -quiet -dumpbase file_lock.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/file-lock-f6b94f5e5d1894a8/out/ea708c7824d36062-file_lock.o -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC ...\n9.703   as               814368 814364   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/file-lock-f6b94f5e5d1894a8/out/ea708c7824d36062-file_lock.o /tmp/cc2bZQnz.s\n9.713   aarch64-linux-g  814370 814359   0 /usr/bin/aarch64-linux-gnu-ar cqD /target/aarch64-unknown-linux-gnu/debug/build/file-lock-f6b94f5e5d1894a8/out/libfile_lock.a /target/aarch64-unknown-linux-gnu/debug/build/file-lock-f6b94f5e5d1894a8/out/ea708c7824d36062-file_lock.o\n9.716   aarch64-linux-g  814371 814359   0 /usr/bin/aarch64-linux-gnu-ar sD /target/aarch64-unknown-linux-gnu/debug/build/file-lock-f6b94f5e5d1894a8/out/libfile_lock.a\n9.721   rustc            814373 814155   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name file_lock --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=33723ec93a77dd2f ...\n9.773   rustc            814396 814221   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 bindings/rust/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=325df26c51708d57 ...\n9.814   cc               814413 814396   0 /tmp/native-trace-814143-1783997018737/shims/cc -m64 /target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n9.814   cc               814414 814413   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n9.817   collect2         814415 814414   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxRIvXm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n9.819   ld.lld           814416 814415   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxRIvXm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082 ...\n9.820   rust-lld         814416 814415   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxRIvXm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n9.882   build-script-bu  814434 814221   0 /target/debug/build/tree-sitter-java-b1b5fbae82b88082/build-script-build\n9.883   powerpc64le-lin  814435 814434   0 /usr/bin/powerpc64le-linux-gnu-gcc -E /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/13831713749963907173detect_compiler_fami\n9.884   cc1              814436 814435   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -imultiarch powerpc64le-linux-gnu /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/13831713749963907173detect_compiler_fami -msecure-plt -mcpu=power8 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n9.889   powerpc64le-lin  814437 814434   0 /usr/bin/powerpc64le-linux-gnu-gcc -?\n9.892   powerpc64le-lin  814438 814434   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I src -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o -c src/parser.c\n9.893   cc1              814439 814438   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I src -imultiarch powerpc64le-linux-gnu src/parser.c -msecure-plt -quiet -dumpbase parser.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o -g -gdwarf-4 -O0 -Wall -Wextra ...\n10.087  as               814440 814438   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I src -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o /tmp/ccsrdoca.s\n10.093  runc             814442 810767   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3b46886501ccd7fcca6ba4ca379e3386839ba0c23f262bf08939523b67c --log-format json --systemd-cgroup kill --all 3b46886501ccd7fcca6ba4ca379e3386839ba0c23f262bf08939523b67cf96a6 9\n10.109  runc             814448 810767   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3b46886501ccd7fcca6ba4ca379e3386839ba0c23f262bf08939523b67c --log-format json --systemd-cgroup delete 3b46886501ccd7fcca6ba4ca379e3386839ba0c23f262bf08939523b67cf96a6\n10.115  powerpc64le-lin  814454 814434   0 /usr/bin/powerpc64le-linux-gnu-ar cqD /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/libtree-sitter-java.a /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o\n10.118  powerpc64le-lin  814455 814434   0 /usr/bin/powerpc64le-linux-gnu-ar sD /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/libtree-sitter-java.a\n10.124  rustc            814457 814221   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_java --edition=2021 bindings/rust/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=456ee8e8757d3710 ...\n10.162  runc             814465 810582   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/87837031b3add06156ac511ff5193387979842194bdb3bc2194361fac45 --log-format json --systemd-cgroup kill --all 87837031b3add06156ac511ff5193387979842194bdb3bc2194361fac451c8d5 9\n10.179  runc             814471 810582   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/87837031b3add06156ac511ff5193387979842194bdb3bc2194361fac45 --log-format json --systemd-cgroup delete 87837031b3add06156ac511ff5193387979842194bdb3bc2194361fac451c8d5\n10.321  containerd-shim  814478 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 3b46886501ccd7fcca6ba4ca379e3386839ba0c23f262bf08939523b67cf96a6 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3b46886501ccd7fcca6ba4ca379e3386839ba0c23f262bf08939523b67c delete\n10.323  runc             814485 814478   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3b46886501ccd7fcca6ba4ca379e3386839ba0c23f262bf08939523b67cf96a --log-format json delete --force 3b46886501ccd7fcca6ba4ca379e3386839ba0c23f262bf08939523b67cf96a6\n10.371  sh               814493 814490   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth6db6322\n10.372  ethtool          814494 814493   0 /usr/sbin/ethtool -i veth6db6322\n10.372  sed              814495 814493   0 /usr/bin/sed -n s/^driver: //p\n10.378  systemd-sysctl   814499 814490   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth6db6322 --prefix=/net/ipv4/neigh/veth6db6322 --prefix=/net/ipv6/conf/veth6db6322 --prefix=/net/ipv6/neigh/veth6db6322\n10.476  containerd-shim  814501 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 87837031b3add06156ac511ff5193387979842194bdb3bc2194361fac451c8d5 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/87837031b3add06156ac511ff5193387979842194bdb3bc2194361fac45 delete\n10.479  runc             814508 814501   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/87837031b3add06156ac511ff5193387979842194bdb3bc2194361fac451c8d --log-format json delete --force 87837031b3add06156ac511ff5193387979842194bdb3bc2194361fac451c8d5\n10.514  systemd-sysctl   814513 814490   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2b80805 --prefix=/net/ipv4/neigh/veth2b80805 --prefix=/net/ipv6/conf/veth2b80805 --prefix=/net/ipv6/neigh/veth2b80805\n11.604  cross            814515 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n11.605  rustc            814518 814515   0 /home/xmoe/.cargo/bin/rustc --print target-list\n11.612  rustc            814518 814515   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n11.626  rustc            814530 814515   0 /home/xmoe/.cargo/bin/rustc -vV\n11.632  rustc            814530 814515   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n11.644  cargo            814540 814515   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n11.651  cargo            814540 814515   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n11.664  rustc            814549 814540   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n11.675  rustc            814551 814540   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n11.689  rustc            814555 814540   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n11.823  rustc            814560 814540   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n11.846  rustc            814562 814515   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n11.854  rustc            814562 814515   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n11.868  docker           814574 814515   0 /usr/bin/docker --help\n11.884  docker           814585 814515   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n11.898  runc             814595 1599     0 /usr/bin/runc --version\n11.901  docker-init      814601 1599     0 /usr/bin/docker-init --version\n11.903  docker           814602 814515   0 /usr/bin/docker info -f {{.SecurityOptions}}\n11.916  runc             814613 1599     0 /usr/bin/runc --version\n11.920  docker-init      814619 1599     0 /usr/bin/docker-init --version\n11.945  rustup           814620 814515   0 /home/xmoe/.cargo/bin/rustup toolchain list\n11.953  rustup           814629 814515   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n11.983  rustup           814638 814515   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n12.010  uname            814647 814515   0 /usr/bin/uname -r\n12.024  docker           814648 814515   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n12.058  systemd-sysctl   814661 814490   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethdc4b4d4 --prefix=/net/ipv4/neigh/vethdc4b4d4 --prefix=/net/ipv6/conf/vethdc4b4d4 --prefix=/net/ipv6/neigh/vethdc4b4d4\n12.058  systemd-sysctl   814662 814514   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb599a89 --prefix=/net/ipv4/neigh/vethb599a89 --prefix=/net/ipv6/conf/vethb599a89 --prefix=/net/ipv6/neigh/vethb599a89\n12.072  containerd-shim  814693 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 5fe98d9bcf5cacd10b943b6646b1a66cd198c16423f088dfff5d30ff2ff35d07 start\n12.075  containerd-shim  814700 814693   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 5fe98d9bcf5cacd10b943b6646b1a66cd198c16423f088dfff5d30ff2ff35d07 -address /var/run/docker/containerd/containerd.sock\n12.079  runc             814710 814700   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5fe98d9bcf5cacd10b943b6646b1a66cd198c16423f088dfff5d30ff2ff --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5fe98d9bcf5cacd10b943b6646b1a66cd198c16423f088dfff5d30ff2ff --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5fe98d9bcf5cacd10b943b6646b1a66cd198c16423f088dfff5d30ff2ff 5fe98d9bcf5cacd10b943b6646b1a66cd198c16423f088dfff5d30ff2ff35d07\n12.083  exe              814717 814710   0 /proc/self/exe init\n12.116  exe              814727 814710   0 /proc/1599/exe -exec-root=/var/run/docker 5fe98d9bcf5cacd10b943b6646b1a66cd198c16423f088dfff5d30ff2ff35d07 d7da31e8f8e1\n12.135  exe              814734 1599     0 /proc/self/exe /var/run/docker/netns/cd87fd8fb70d all false\n12.181  runc             814753 814700   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5fe98d9bcf5cacd10b943b6646b1a66cd198c16423f088dfff5d30ff2ff --log-format json --systemd-cgroup start 5fe98d9bcf5cacd10b943b6646b1a66cd198c16423f088dfff5d30ff2ff35d07\n12.186  sh               814721 814700   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n12.186  cargo            814759 814721   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n12.196  cargo-native-tr  814759 814721   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n12.199  cargo            814760 814759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n12.210  rustc            814761 814760   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n12.222  rustc            814763 814760   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n12.240  execsnoop        814767 814759   0 /usr/local/bin/execsnoop -t\n12.241  python3          814767 814759   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n12.369  runc             814770 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process4142851923 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n12.374  exe              814777 814770   0 /proc/self/exe init\n12.399  etcdctl          814780 814770   0 /usr/local/bin/etcdctl endpoint health\n13.036  16               814795 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n13.054  frpc             814795 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n14.183  cargo            814801 814759   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n14.195  rustc            814802 814801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n14.215  rustc            814810 814801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name find_msvc_tools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n14.215  rustc            814811 814801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n14.216  rustc            814812 814801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n14.276  rustc            814830 814801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n14.331  cc               814840 814812   0 /tmp/native-trace-814759-1783997023809/shims/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcD14q7p/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n14.332  cc               814841 814840   0 /usr/bin/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcD14q7p/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n14.334  collect2         814842 814841   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBhLJSG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n14.336  ld.lld           814843 814842   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBhLJSG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db ...\n14.336  rust-lld         814843 814842   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBhLJSG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n14.376  build-script-bu  814861 814801   0 /target/debug/build/libc-8a22300c8f78b6db/build-script-build\n14.377  rustc            814862 814861   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n14.389  rustc            814866 814801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n14.881  rustc            814892 814801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=06b7662075ecae39 ...\n14.915  cc               814906 814892   0 /tmp/native-trace-814759-1783997023809/shims/cc -m64 /target/debug/build/file-lock-e7ec189e8a3c419e/rustcamM1WB/symbols.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.3c3psple0gmv7yyyqbp3fgtcd.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.401d3kyjceojcgroawg6c9nf0.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.56ucri67nlogpucsi59dqr1hc.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.8cjtzgjhebof5tgf3ur55jtke.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.9mq8ou3x1tjs9nkpxzempsbhb.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.bm7tz27hlft2omjdgnf6azk3u.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.c7qrznfrt7tj7vr46f9y3pxbi.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.e4wu78s2munsd8k0hgjdupuy7.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.71a4npaby13yh9u2xmrbik0dn.0fbramd.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n14.916  cc               814907 814906   0 /usr/bin/cc -m64 /target/debug/build/file-lock-e7ec189e8a3c419e/rustcamM1WB/symbols.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.3c3psple0gmv7yyyqbp3fgtcd.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.401d3kyjceojcgroawg6c9nf0.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.56ucri67nlogpucsi59dqr1hc.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.8cjtzgjhebof5tgf3ur55jtke.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.9mq8ou3x1tjs9nkpxzempsbhb.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.bm7tz27hlft2omjdgnf6azk3u.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.c7qrznfrt7tj7vr46f9y3pxbi.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.e4wu78s2munsd8k0hgjdupuy7.0fbramd.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.71a4npaby13yh9u2xmrbik0dn.0fbramd.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n14.918  collect2         814908 814907   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc4HdQe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n14.919  ld.lld           814909 814908   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc4HdQe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e ...\n14.920  rust-lld         814909 814908   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc4HdQe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n14.974  build-script-bu  814927 814801   0 /target/debug/build/file-lock-e7ec189e8a3c419e/build-script-build\n14.975  riscv64-linux-g  814928 814927   0 /usr/bin/riscv64-linux-gnu-gcc -E /target/riscv64gc-unknown-linux-gnu/debug/build/file-lock-7682ed3b3f968295/out/4518273080423325231detect_compiler_family.c\n14.976  cc1              814929 814928   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/file-lock-7682ed3b3f968295/out/4518273080423325231detect_compiler_family.c -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -fstack-protector-strong -Wformat -Wformat-security -dumpbase 4518273080423325231detect_compiler_family.c -dumpbase-ext .c\n14.981  riscv64-linux-g  814930 814927   0 /usr/bin/riscv64-linux-gnu-gcc -?\n14.984  riscv64-linux-g  814931 814927   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/file-lock-7682ed3b3f968295/out/ea708c7824d36062-file_lock.o -c src/file_lock.c\n14.985  cc1              814932 814931   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu src/file_lock.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/file-lock-7682ed3b3f968295/out/ -dumpbase ea708c7824d36062-file_lock.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g -gdwarf-4 ...\n14.997  as               814933 814931   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/file-lock-7682ed3b3f968295/out/ea708c7824d36062-file_lock.o /tmp/ccUEbCuy.s\n14.999  riscv64-linux-g  814934 814927   0 /usr/bin/riscv64-linux-gnu-ar cqD /target/riscv64gc-unknown-linux-gnu/debug/build/file-lock-7682ed3b3f968295/out/libfile_lock.a /target/riscv64gc-unknown-linux-gnu/debug/build/file-lock-7682ed3b3f968295/out/ea708c7824d36062-file_lock.o\n15.015  riscv64-linux-g  814935 814927   0 /usr/bin/riscv64-linux-gnu-ar sD /target/riscv64gc-unknown-linux-gnu/debug/build/file-lock-7682ed3b3f968295/out/libfile_lock.a\n15.034  rustc            814937 814801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name file_lock --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=80fcdc70949e12f0 ...\n17.191  runc             814957 811662   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4fd8cd13e6fe4cd3bbbd1d1c3e6ae2ed357f3b762c8f19a46dd198093ec --log-format json --systemd-cgroup kill --all 4fd8cd13e6fe4cd3bbbd1d1c3e6ae2ed357f3b762c8f19a46dd198093ec69bfc 9\n17.210  runc             814964 811662   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4fd8cd13e6fe4cd3bbbd1d1c3e6ae2ed357f3b762c8f19a46dd198093ec --log-format json --systemd-cgroup delete 4fd8cd13e6fe4cd3bbbd1d1c3e6ae2ed357f3b762c8f19a46dd198093ec69bfc\n17.377  containerd-shim  814970 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 4fd8cd13e6fe4cd3bbbd1d1c3e6ae2ed357f3b762c8f19a46dd198093ec69bfc -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4fd8cd13e6fe4cd3bbbd1d1c3e6ae2ed357f3b762c8f19a46dd198093ec delete\n17.380  runc             814976 814970   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4fd8cd13e6fe4cd3bbbd1d1c3e6ae2ed357f3b762c8f19a46dd198093ec69bf --log-format json delete --force 4fd8cd13e6fe4cd3bbbd1d1c3e6ae2ed357f3b762c8f19a46dd198093ec69bfc\n17.426  systemd-sysctl   814983 814982   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe83f654 --prefix=/net/ipv4/neigh/vethe83f654 --prefix=/net/ipv6/conf/vethe83f654 --prefix=/net/ipv6/neigh/vethe83f654\n17.553  runc             814985 811685   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3e28ab9136f3f75a4852e40d8b9d77b153275104a4e3d926d76c36d9936 --log-format json --systemd-cgroup kill --all 3e28ab9136f3f75a4852e40d8b9d77b153275104a4e3d926d76c36d9936c39a4 9\n17.561  runc             814992 811685   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3e28ab9136f3f75a4852e40d8b9d77b153275104a4e3d926d76c36d9936 --log-format json --systemd-cgroup delete 3e28ab9136f3f75a4852e40d8b9d77b153275104a4e3d926d76c36d9936c39a4\n17.767  containerd-shim  814998 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 3e28ab9136f3f75a4852e40d8b9d77b153275104a4e3d926d76c36d9936c39a4 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3e28ab9136f3f75a4852e40d8b9d77b153275104a4e3d926d76c36d9936 delete\n17.770  runc             815004 814998   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3e28ab9136f3f75a4852e40d8b9d77b153275104a4e3d926d76c36d9936c39a --log-format json delete --force 3e28ab9136f3f75a4852e40d8b9d77b153275104a4e3d926d76c36d9936c39a4\n17.807  runc             815011 811663   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/86de489dd7ba965d8738fb3dfd51ebc7644fad87286066b04f9738e5485 --log-format json --systemd-cgroup kill --all 86de489dd7ba965d8738fb3dfd51ebc7644fad87286066b04f9738e548503529 9\n17.814  systemd-sysctl   815017 814982   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth6616e51 --prefix=/net/ipv4/neigh/veth6616e51 --prefix=/net/ipv6/conf/veth6616e51 --prefix=/net/ipv6/neigh/veth6616e51\n17.815  runc             815018 811663   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/86de489dd7ba965d8738fb3dfd51ebc7644fad87286066b04f9738e5485 --log-format json --systemd-cgroup delete 86de489dd7ba965d8738fb3dfd51ebc7644fad87286066b04f9738e548503529\n17.988  containerd-shim  815025 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 86de489dd7ba965d8738fb3dfd51ebc7644fad87286066b04f9738e548503529 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/86de489dd7ba965d8738fb3dfd51ebc7644fad87286066b04f9738e5485 delete\n17.991  runc             815032 815025   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/86de489dd7ba965d8738fb3dfd51ebc7644fad87286066b04f9738e54850352 --log-format json delete --force 86de489dd7ba965d8738fb3dfd51ebc7644fad87286066b04f9738e548503529\n18.031  systemd-sysctl   815037 814982   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth005461e --prefix=/net/ipv4/neigh/veth005461e --prefix=/net/ipv6/conf/veth005461e --prefix=/net/ipv6/neigh/veth005461e\n"
    },
    {
      "argv": [
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 813266,
      "build_script_target_dir": "tree-sitter-language-04f523abf8aa8aa2",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build",
      "pid": 813266,
      "ppid": 813211,
      "root_cargo_pid": 813211,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 813473,
      "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build-script-build",
      "pid": 813473,
      "ppid": 813211,
      "root_cargo_pid": 813211,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-E",
        "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/4954000664577432107detect_compiler_family.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 813473,
      "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 813475,
      "ppid": 813473,
      "root_cargo_pid": 813211,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-E",
        "-quiet",
        "-imultiarch",
        "aarch64-linux-gnu",
        "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/4954000664577432107detect_compiler_family.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 813473,
      "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 813476,
      "ppid": 813475,
      "root_cargo_pid": 813211,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 813473,
      "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 813479,
      "ppid": 813473,
      "root_cargo_pid": 813211,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-std=c11",
        "-I",
        "src",
        "-Wall",
        "-Wextra",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/ea708c7824d36062-parser.o",
        "-c",
        "src/parser.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 813473,
      "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 813480,
      "ppid": 813473,
      "root_cargo_pid": 813211,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "src",
        "-imultiarch",
        "aarch64-linux-gnu",
        "src/parser.c",
        "-quiet",
        "-dumpbase",
        "parser.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/ea708c7824d36062-parser.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-Wall",
        "-Wextra",
        "-std=c11",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 813473,
      "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 813481,
      "ppid": 813480,
      "root_cargo_pid": 813211,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-I",
        "src",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/ea708c7824d36062-parser.o",
        "/tmp/ccpXze2J.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 813473,
      "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 813520,
      "ppid": 813480,
      "root_cargo_pid": 813211,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "cqD",
        "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/libtree-sitter-java.a",
        "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/ea708c7824d36062-parser.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 813473,
      "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 813521,
      "ppid": 813473,
      "root_cargo_pid": 813211,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "sD",
        "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-java-a41fe43f475216af/out/libtree-sitter-java.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 813473,
      "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 813522,
      "ppid": 813473,
      "root_cargo_pid": 813211,
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
      "crate": "tree-sitter-java",
      "cwd": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "event_id": "bsrun:076a9138da0c3f07:5b4e52ebebf54619:416f8f7a19a7071a",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
      "out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
      "success": true,
      "target": null,
      "version": "0.23.5",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-aarch64-2732ibto/src/tree-sitter-java-0.23.5",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
  "item": {
    "rank": 3138,
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "crate_id": "306053",
    "version_id": "1382692",
    "downloads": 3442726,
    "cumulative_downloads": 107365932574,
    "cumulative_share_of_global": 0.4014164358443001,
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
