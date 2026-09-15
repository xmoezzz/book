# `tree-sitter-java` `0.23.5`

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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b",
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
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-814413-1783997021427401226.map",
  "pid": 814413,
  "ppid": 814396,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-814413-1783997021427401226.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/libtree-sitter-java.a`

Owner: `tree-sitter-java` `0.23.5`

### Source files

* `/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5/src/parser.c`

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
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o",
    "-c",
    "src/parser.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 814434,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 814438,
  "ppid": 814434,
  "root_cargo_pid": 814221,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "src/parser.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "parser.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "..."
  ],
  "src": "src/parser.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 814439,
  "ppid": 814438,
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "root_cargo_pid": 814221,
  "build_script_root_pid": 814434,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
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
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/libtree-sitter-java.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o"
  ],
  "archive": "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/libtree-sitter-java.a",
  "objects": [
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 814454,
  "ppid": 814434,
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "root_cargo_pid": 814221,
  "build_script_root_pid": 814434,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "workspace_root": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5"
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
      "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
      "name": "tree-sitter-java",
      "version": "0.23.5",
      "manifest_path": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5"
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/raw-dylibs",
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
  "pid": 814248,
  "ppid": 814235,
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/raw-dylibs",
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
  "event_id": "used:cc:d9861ad91616b5cc:c1d12c051337faa0:085e3bf50b18abef",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
  "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o",
  "pid": 814248,
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/raw-dylibs",
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
  "pid": 814248,
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/raw-dylibs",
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
  "pid": 814248,
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/raw-dylibs",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/raw-dylibs",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/raw-dylibs",
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
  "context_path": "/tmp/native-trace-814143-1783997018737/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-814143-1783997018737/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 814248,
  "ppid": 814235,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/raw-dylibs",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u",
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
      "directory": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o",
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
  "map_path": "/tmp/native-trace-link-cc-814248-1783997020703120745.map",
  "pid": 814248,
  "ppid": 814235,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-814248-1783997020703120745.map"
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "exit_code": 0,
  "kind": "exec",
  "pid": 814413,
  "ppid": 814396,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:23e5ba707569c0c7:a27f607962838c1e:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
  "pid": 814413,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:23e5ba707569c0c7:49d398cdf3d95d60:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
  "pid": 814413,
  "sha256": "c89f41dcce91c8e376665d637194d4ff438cde95fae307bc05c4d723c4337709",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:23e5ba707569c0c7:4d166e250a9c3d38:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
  "pid": 814413,
  "sha256": "31909db1816b6e599643976d64006df1954956bdb43f9e21ed6a000e342a7b44",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:23e5ba707569c0c7:d89591db5739b89b:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
  "pid": 814413,
  "sha256": "75fb961da3f58aeeb57ab792ef21de87322fc28e95592c368c68e94a22c126fb",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:23e5ba707569c0c7:3fe383c7b72a2c85:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
  "pid": 814413,
  "sha256": "af4875b4c44928e348197cc39309f1990ae1a60d08eb21fe4e6a819cef408d24",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:23e5ba707569c0c7:ec5e68c5d2606a22:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
  "pid": 814413,
  "sha256": "425e080599ca64030671b67fa226f456b182394b78556b99bc7b78a95fafe9f5",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:23e5ba707569c0c7:bffb1ece99f57ec6:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
  "pid": 814413,
  "sha256": "e3824b064a0622d6a9b11e8140c48f967a32c450432fe78b036c24386d0c11c6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:23e5ba707569c0c7:a3da80c9a0a91597:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
  "pid": 814413,
  "sha256": "74b13806e1f766786cf02ba3c672d591b93c02d4e96c21d29979b42f7999a32f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:23e5ba707569c0c7:b2906c80f49aa777:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
  "pid": 814413,
  "sha256": "535a8168022e7a8fa61b98bb80606470a9e505db643e9f8a5b515e550e6f4b19",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:23e5ba707569c0c7:8becfad388957269:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
  "pid": 814413,
  "sha256": "72d7a0f727472cd9e2385cc7c47cdde04d5ef9743dda0930213f2f523bc3fe3e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:23e5ba707569c0c7:26dd2a5e7828239a:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
  "pid": 814413,
  "sha256": "5d3552dcfe6396a9858071fd9dbffb5bcd3583bd5d889d6f911f50313b8a23e5",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:23e5ba707569c0c7:c5dbceecd4e81526:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
  "pid": 814413,
  "sha256": "87189e9ad602ccfa929a0c09c2d521106d7b08f6bde6616b40bbc3a646af2ebd",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "event_id": "used:cc:23e5ba707569c0c7:498d12d8fed5a13c:9d8c5a4c27d804b4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
  "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
  "pid": 814413,
  "sha256": "75468453c13ef230dac3751b703b1015b0a13f788d7cdd74029370ef9cdb8fcd",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "cargo_pkg_name": "tree-sitter-java",
  "cargo_pkg_version": "0.23.5",
  "context_path": "/tmp/native-trace-814143-1783997018737/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-814143-1783997018737/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 814413,
  "ppid": 814396,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b",
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
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-814413-1783997021427401226.map",
  "pid": 814413,
  "ppid": 814396,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-814413-1783997021427401226.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
  "parsed_event_count": 451,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 452,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "1fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n13.191  collect2         815730 815728   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbw5DtH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.193  ld.lld           815736 815730   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbw5DtH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/io-lifetimes-963751d69e961f50/build_script_build-963751d69e961f50 ...\n13.194  rust-lld         815736 815730   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbw5DtH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.195  cc               815731 815607   0 /tmp/native-trace-815545-1783997031660/shims/cc -m64 /target/debug/build/io-extras-cb8206428352439e/rustcjGY8Eg/symbols.o /target/debug/build/io-extras-cb8206428352439e/build_script_build-cb8206428352439e.build_script_build.8266330570a55331-cgu.0.rcg /target/debug/build/io-extras-cb8206428352439e/build_script_build-cb8206428352439e.build_script_build.8266330570a55331-cgu.1.rcg /target/debug/build/io-extras-cb8206428352439e/build_script_build-cb8206428352439e.b2taiobdfsr84pimy1fnnf8wx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n13.198  cc               815743 815731   0 /usr/bin/cc -m64 /target/debug/build/io-extras-cb8206428352439e/rustcjGY8Eg/symbols.o /target/debug/build/io-extras-cb8206428352439e/build_script_build-cb8206428352439e.build_script_build.8266330570a55331-cgu.0.rcg /target/debug/build/io-extras-cb8206428352439e/build_script_build-cb8206428352439e.build_script_build.8266330570a55331-cgu.1.rcg /target/debug/build/io-extras-cb8206428352439e/build_script_build-cb8206428352439e.b2taiobdfsr84pimy1fnnf8wx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n13.205  collect2         815747 815743   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cca2q5PQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.207  ld.lld           815751 815747   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cca2q5PQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/io-extras-cb8206428352439e/build_script_build-cb8206428352439e ...\n13.208  rust-lld         815751 815747   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cca2q5PQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.230  cc               815793 815613   0 /tmp/native-trace-815545-1783997031660/shims/cc -m64 /target/debug/build/cap-primitives-806b2f1f5f1bc65b/rustcdgw8u5/symbols.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.0fdkdi7bwb7ms5x1w080ify2t.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.0rb6bl0t2sn5ttnmy0ll2fffi.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.0tipwih5021yrg006n0kvxn46.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.0vajyxwrtlhb21ahl339e1ann.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.1bp6sok1pqwy49ckfj76dz1ls.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.221240crkdriedvxrg1r6opf8.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.45oqd6sy3ynchq85aerdcc7ea.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.46fqj1tmaem958co8ba9j45yt.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.47khdddzqr2gxzu2bwnwyobqt.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.48b2y44akgsqgwomqhw141hnt.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.4d5ph18g5ln39b7muu1x1vnie.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.4itttmqhfcupwlihyhzhsflec.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.4yul106ehyxfh2k9vfqcrayps.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.51a2f7wb5nyfoaitzfpi2dpjw.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.55y8pfs1qmwtuq6x1nqruliw6.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.569hibj8ed1sxl75ovb9pro69.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.59d29kdnlw1k9z8b5fmcckyzr.1mi1vyz.rcgu.o ...\n13.233  cc               815795 815793   0 /usr/bin/cc -m64 /target/debug/build/cap-primitives-806b2f1f5f1bc65b/rustcdgw8u5/symbols.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.0fdkdi7bwb7ms5x1w080ify2t.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.0rb6bl0t2sn5ttnmy0ll2fffi.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.0tipwih5021yrg006n0kvxn46.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.0vajyxwrtlhb21ahl339e1ann.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.1bp6sok1pqwy49ckfj76dz1ls.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.221240crkdriedvxrg1r6opf8.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.45oqd6sy3ynchq85aerdcc7ea.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.46fqj1tmaem958co8ba9j45yt.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.47khdddzqr2gxzu2bwnwyobqt.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.48b2y44akgsqgwomqhw141hnt.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.4d5ph18g5ln39b7muu1x1vnie.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.4itttmqhfcupwlihyhzhsflec.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.4yul106ehyxfh2k9vfqcrayps.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.51a2f7wb5nyfoaitzfpi2dpjw.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.55y8pfs1qmwtuq6x1nqruliw6.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.569hibj8ed1sxl75ovb9pro69.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.59d29kdnlw1k9z8b5fmcckyzr.1mi1vyz.rcgu.o ...\n13.236  collect2         815796 815795   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchif2PO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.238  ld.lld           815798 815796   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchif2PO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b ...\n13.241  cc               815797 815588   0 /tmp/native-trace-815554-1783997031673/shims/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustciP1E9c/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n13.241  rust-lld         815798 815796   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchif2PO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.241  cc               815799 815797   0 /usr/bin/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustciP1E9c/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n13.245  collect2         815800 815799   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHYtlm4.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.247  ld.lld           815802 815800   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHYtlm4.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db ...\n13.248  rust-lld         815802 815800   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHYtlm4.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.250  cc               815801 815602   0 /tmp/native-trace-815545-1783997031660/shims/cc -m64 /target/debug/build/rustix-8b04315b121d1c9e/rustcmfvyBM/symbols.o /target/debug/build/rustix-8b04315b121d1c9e/build_script_build-8b04315b121d1c9e.build_script_build.d69df35ee93463f2-cgu.0.rcgu.o /target/debug/build/rustix-8b04315b121d1c9e/build_script_build-8b04315b121d1c9e.build_script_build.d69df35ee93463f2-cgu.1.rcgu.o /target/debug/build/rustix-8b04315b121d1c9e/build_script_build-8b04315b121d1c9e.build_script_build.d69df35ee93463f2-cgu.2.rcgu.o /target/debug/build/rustix-8b04315b121d1c9e/build_script_build-8b04315b121d1c9e.95ev0x7gi623yv044fvtecfu2.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n13.251  cc               815803 815801   0 /usr/bin/cc -m64 /target/debug/build/rustix-8b04315b121d1c9e/rustcmfvyBM/symbols.o /target/debug/build/rustix-8b04315b121d1c9e/build_script_build-8b04315b121d1c9e.build_script_build.d69df35ee93463f2-cgu.0.rcgu.o /target/debug/build/rustix-8b04315b121d1c9e/build_script_build-8b04315b121d1c9e.build_script_build.d69df35ee93463f2-cgu.1.rcgu.o /target/debug/build/rustix-8b04315b121d1c9e/build_script_build-8b04315b121d1c9e.build_script_build.d69df35ee93463f2-cgu.2.rcgu.o /target/debug/build/rustix-8b04315b121d1c9e/build_script_build-8b04315b121d1c9e.95ev0x7gi623yv044fvtecfu2.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n13.256  collect2         815818 815803   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0Vv2no.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.257  ld.lld           815821 815818   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0Vv2no.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rustix-8b04315b121d1c9e/build_script_build-8b04315b121d1c9e ...\n13.260  rust-lld         815821 815818   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0Vv2no.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.267  cc               815838 815598   0 /tmp/native-trace-815545-1783997031660/shims/cc -m64 /target/debug/build/rustix-3ab2da0310f54ee6/rustcAwr86L/symbols.o /target/debug/build/rustix-3ab2da0310f54ee6/build_script_build-3ab2da0310f54ee6.build_script_build.ac56497bb95cd8d6-cgu.0.rcgu.o /target/debug/build/rustix-3ab2da0310f54ee6/build_script_build-3ab2da0310f54ee6.build_script_build.ac56497bb95cd8d6-cgu.1.rcgu.o /target/debug/build/rustix-3ab2da0310f54ee6/build_script_build-3ab2da0310f54ee6.build_script_build.ac56497bb95cd8d6-cgu.2.rcgu.o /target/debug/build/rustix-3ab2da0310f54ee6/build_script_build-3ab2da0310f54ee6.2iz47d1t5ckh71bpj3gcc8sdp.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n13.269  cc               815839 815838   0 /usr/bin/cc -m64 /target/debug/build/rustix-3ab2da0310f54ee6/rustcAwr86L/symbols.o /target/debug/build/rustix-3ab2da0310f54ee6/build_script_build-3ab2da0310f54ee6.build_script_build.ac56497bb95cd8d6-cgu.0.rcgu.o /target/debug/build/rustix-3ab2da0310f54ee6/build_script_build-3ab2da0310f54ee6.build_script_build.ac56497bb95cd8d6-cgu.1.rcgu.o /target/debug/build/rustix-3ab2da0310f54ee6/build_script_build-3ab2da0310f54ee6.build_script_build.ac56497bb95cd8d6-cgu.2.rcgu.o /target/debug/build/rustix-3ab2da0310f54ee6/build_script_build-3ab2da0310f54ee6.2iz47d1t5ckh71bpj3gcc8sdp.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n13.271  collect2         815840 815839   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9c3eD9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.274  ld.lld           815848 815840   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9c3eD9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rustix-3ab2da0310f54ee6/build_script_build-3ab2da0310f54ee6 ...\n13.275  rust-lld         815848 815840   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9c3eD9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.292  build-script-bu  815859 815574   0 /target/debug/build/io-lifetimes-963751d69e961f50/build-script-build\n13.294  build-script-bu  815877 815574   0 /target/debug/build/io-extras-cb8206428352439e/build-script-build\n13.296  rustc            815880 815877   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --target aarch64-unknown-linux-gnu --out-dir /target/aarch64-unknown-linux-gnu/debug/build/io-extras-c5caa310b5200703/out -\n13.297  rustc            815879 815574   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name io_lifetimes --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/io-lifetimes-2.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(wasi_ext) --cfg feature=\"default\" --check-cfg ...\n13.317  build-script-bu  815892 815575   0 /target/debug/build/libc-8a22300c8f78b6db/build-script-build\n13.317  build-script-bu  815891 815574   0 /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build-script-build\n13.319  rustc            815894 815892   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n13.319  rustc            815893 815877   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --target aarch64-unknown-linux-gnu --out-dir /target/aarch64-unknown-linux-gnu/debug/build/io-extras-c5caa310b5200703/out -\n13.319  rustc            815895 815891   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --out-dir /target/aarch64-unknown-linux-gnu/debug/build/cap-primitives-0c2defdabe916bb3/out -\n13.335  build-script-bu  815907 815574   0 /target/debug/build/rustix-8b04315b121d1c9e/build-script-build\n13.338  rustc            815909 815575   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n13.338  rustc            815910 815907   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --target aarch64-unknown-linux-gnu -o - -\n13.345  rustc            815917 815891   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --out-dir /target/aarch64-unknown-linux-gnu/debug/build/cap-primitives-0c2defdabe916bb3/out -\n13.350  build-script-bu  815931 815574   0 /target/debug/build/rustix-3ab2da0310f54ee6/build-script-build\n13.350  rustc            815928 815574   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name io_extras --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/io-extras-0.18.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(can_vector) --check-cfg cfg(write_all_vectored) --cfg ...\n13.352  rustc            815932 815931   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --target aarch64-unknown-linux-gnu -o /target/aarch64-unknown-linux-gnu/debug/build/rustix-bd0120e3184d440a/out/rustix_test_can_compile -\n13.368  rustc            815944 815574   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rustix --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.44/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(alloc_c_string) --check-cfg cfg(alloc_ffi) --check-cfg ...\n13.373  rustc            815945 815891   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --out-dir /target/aarch64-unknown-linux-gnu/debug/build/cap-primitives-0c2defdabe916bb3/out -\n13.378  rustc            815948 815931   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --target aarch64-unknown-linux-gnu -o /target/aarch64-unknown-linux-gnu/debug/build/rustix-bd0120e3184d440a/out/rustix_test_can_compile -\n13.396  rustc            815958 815891   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --out-dir /target/aarch64-unknown-linux-gnu/debug/build/cap-primitives-0c2defdabe916bb3/out -\n13.400  rustc            815959 815931   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --target aarch64-unknown-linux-gnu -o /target/aarch64-unknown-linux-gnu/debug/build/rustix-bd0120e3184d440a/out/rustix_test_can_compile -\n13.422  rustc            815970 815574   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rustix --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-1.1.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(alloc_c_string) --check-cfg cfg(alloc_ffi) --check-cfg ...\n13.951  rustc            815996 815575   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=06b7662075ecae39 ...\n13.986  cc               816010 815996   0 /tmp/native-trace-815554-1783997031673/shims/cc -m64 /target/debug/build/file-lock-e7ec189e8a3c419e/rustcuciSjo/symbols.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.3c3psple0gmv7yyyqbp3fgtcd.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.401d3kyjceojcgroawg6c9nf0.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.56ucri67nlogpucsi59dqr1hc.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.8cjtzgjhebof5tgf3ur55jtke.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.9mq8ou3x1tjs9nkpxzempsbhb.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.bm7tz27hlft2omjdgnf6azk3u.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.c7qrznfrt7tj7vr46f9y3pxbi.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.e4wu78s2munsd8k0hgjdupuy7.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.71a4npaby13yh9u2xmrbik0dn.0vbzgvk.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n13.986  cc               816011 816010   0 /usr/bin/cc -m64 /target/debug/build/file-lock-e7ec189e8a3c419e/rustcuciSjo/symbols.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.3c3psple0gmv7yyyqbp3fgtcd.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.401d3kyjceojcgroawg6c9nf0.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.56ucri67nlogpucsi59dqr1hc.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.8cjtzgjhebof5tgf3ur55jtke.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.9mq8ou3x1tjs9nkpxzempsbhb.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.bm7tz27hlft2omjdgnf6azk3u.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.c7qrznfrt7tj7vr46f9y3pxbi.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.e4wu78s2munsd8k0hgjdupuy7.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.71a4npaby13yh9u2xmrbik0dn.0vbzgvk.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n13.989  collect2         816012 816011   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccP9Ez9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.990  ld.lld           816013 816012   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccP9Ez9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e ...\n13.992  rust-lld         816013 816012   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccP9Ez9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n14.049  build-script-bu  816031 815575   0 /target/debug/build/file-lock-e7ec189e8a3c419e/build-script-build\n14.051  powerpc64le-lin  816032 816031   0 /usr/bin/powerpc64le-linux-gnu-gcc -E /target/powerpc64le-unknown-linux-gnu/debug/build/file-lock-83a95664524a93ab/out/8232646621862039672detect_compiler_family.c\n14.052  cc1              816033 816032   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -imultiarch powerpc64le-linux-gnu /target/powerpc64le-unknown-linux-gnu/debug/build/file-lock-83a95664524a93ab/out/8232646621862039672detect_compiler_family.c -msecure-plt -mcpu=power8 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n14.056  powerpc64le-lin  816034 816031   0 /usr/bin/powerpc64le-linux-gnu-gcc -?\n14.059  powerpc64le-lin  816035 816031   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/file-lock-83a95664524a93ab/out/ea708c7824d36062-file_lock.o -c src/file_lock.c\n14.060  cc1              816036 816035   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu src/file_lock.c -msecure-plt -quiet -dumpbase file_lock.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/file-lock-83a95664524a93ab/out/ea708c7824d36062-file_lock.o -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections ...\n14.075  as               816037 816035   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/file-lock-83a95664524a93ab/out/ea708c7824d36062-file_lock.o /tmp/ccmBp7mY.s\n14.080  powerpc64le-lin  816038 816031   0 /usr/bin/powerpc64le-linux-gnu-ar cqD /target/powerpc64le-unknown-linux-gnu/debug/build/file-lock-83a95664524a93ab/out/libfile_lock.a /target/powerpc64le-unknown-linux-gnu/debug/build/file-lock-83a95664524a93ab/out/ea708c7824d36062-file_lock.o\n14.082  powerpc64le-lin  816039 816031   0 /usr/bin/powerpc64le-linux-gnu-ar sD /target/powerpc64le-unknown-linux-gnu/debug/build/file-lock-83a95664524a93ab/out/libfile_lock.a\n14.086  rustc            816041 815575   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name file_lock --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=9238029ecd562325 ...\n14.404  rustc            816065 815574   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fs_set_times --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fs-set-times-0.20.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=1c3bfbacd5c18ecd ...\n14.968  rustc            816084 815574   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cap_primitives --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\")) -C metadata=cc7fd8781413840f ...\n17.033  cross            816295 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n17.034  rustc            816298 816295   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.041  rustc            816298 816295   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.055  rustc            816310 816295   0 /home/xmoe/.cargo/bin/rustc -vV\n17.062  rustc            816310 816295   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.073  cargo            816320 816295   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n17.079  cargo            816320 816295   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n17.093  rustc            816329 816320   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.105  rustc            816331 816320   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.118  rustc            816335 816320   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.232  cross            816339 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n17.234  rustc            816341 816339   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.241  rustc            816341 816339   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.255  rustc            816354 816339   0 /home/xmoe/.cargo/bin/rustc -vV\n17.261  rustc            816354 816339   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.272  cargo            816364 816339   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n17.278  cargo            816364 816339   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n17.291  rustc            816373 816364   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.303  rustc            816375 816364   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.316  rustc            816379 816364   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.441  rustc            816383 816295   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.447  rustc            816383 816295   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.462  docker           816395 816295   0 /usr/bin/docker --help\n17.468  rustc            816401 816339   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.474  rustc            816401 816339   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.476  docker           816415 816295   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.489  docker           816429 816339   0 /usr/bin/docker --help\n17.489  cross            816430 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n17.490  cross            816432 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n17.490  rustc            816434 816430   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.491  rustc            816442 816432   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.491  runc             816443 1599     0 /usr/bin/runc --version\n17.495  docker-init      816465 1599     0 /usr/bin/docker-init --version\n17.496  docker           816466 816295   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.496  rustc            816434 816430   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.497  rustc            816442 816432   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.505  docker           816476 816339   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.510  rustc            816489 816432   0 /home/xmoe/.cargo/bin/rustc -vV\n17.511  rustc            816490 816430   0 /home/xmoe/.cargo/bin/rustc -vV\n17.512  runc             816491 1599     0 /usr/bin/runc --version\n17.516  docker-init      816517 1599     0 /usr/bin/docker-init --version\n17.517  rustc            816490 816430   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.518  rustc            816489 816432   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.521  runc             816525 1599     0 /usr/bin/runc --version\n17.525  docker-init      816531 1599     0 /usr/bin/docker-init --version\n17.526  docker           816534 816339   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.528  cargo            816540 816432   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n17.529  cargo            816541 816430   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n17.535  cargo            816540 816432   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n17.536  cargo            816541 816430   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n17.541  runc             816559 1599     0 /usr/bin/runc --version\n17.544  rustup           816565 816295   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.545  docker-init      816566 1599     0 /usr/bin/docker-init --version\n17.549  rustc            816575 816540   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.549  rustc            816576 816541   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.552  rustup           816577 816295   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.560  rustc            816588 816540   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.560  rustc            816589 816541   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.571  rustup           816596 816339   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.573  rustc            816597 816541   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.574  rustc            816598 816540   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.578  rustup           816607 816339   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.580  rustup           816608 816295   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.601  rustup           816632 816339   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.602  uname            816633 816295   0 /usr/bin/uname -r\n17.617  docker           816642 816295   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.624  uname            816648 816339   0 /usr/bin/uname -r\n17.640  docker           816654 816339   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.664  systemd-sysctl   816673 816671   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethbf98632 --prefix=/net/ipv4/neigh/vethbf98632 --prefix=/net/ipv6/conf/vethbf98632 --prefix=/net/ipv6/neigh/vethbf98632\n17.665  systemd-sysctl   816674 816672   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc26d400 --prefix=/net/ipv4/neigh/vethc26d400 --prefix=/net/ipv6/conf/vethc26d400 --prefix=/net/ipv6/neigh/vethc26d400\n17.677  containerd-shim  816706 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id d8b5ae84470c392a0f9d6d5ca48ae45dc68f74c3ed1ae62346b75312885628ed start\n17.680  containerd-shim  816714 816706   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id d8b5ae84470c392a0f9d6d5ca48ae45dc68f74c3ed1ae62346b75312885628ed -address /var/run/docker/containerd/containerd.sock\n17.684  runc             816724 816714   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d8b5ae84470c392a0f9d6d5ca48ae45dc68f74c3ed1ae62346b75312885 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d8b5ae84470c392a0f9d6d5ca48ae45dc68f74c3ed1ae62346b75312885 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d8b5ae84470c392a0f9d6d5ca48ae45dc68f74c3ed1ae62346b75312885 d8b5ae84470c392a0f9d6d5ca48ae45dc68f74c3ed1ae62346b75312885628ed\n17.689  exe              816731 816724   0 /proc/self/exe init\n17.690  systemd-sysctl   816735 816691   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth30a7b37 --prefix=/net/ipv4/neigh/veth30a7b37 --prefix=/net/ipv6/conf/veth30a7b37 --prefix=/net/ipv6/neigh/veth30a7b37\n17.690  systemd-sysctl   816734 816701   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe31eb68 --prefix=/net/ipv4/neigh/vethe31eb68 --prefix=/net/ipv6/conf/vethe31eb68 --prefix=/net/ipv6/neigh/vethe31eb68\n17.703  cross            816738 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n17.704  rustc            816745 816738   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.708  containerd-shim  816755 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a3341f91925ec20439d9c3ddd28bcd2b91701139f94faa11c3fc1b2b20e27552 start\n17.710  rustc            816745 816738   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.710  containerd-shim  816762 816755   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id a3341f91925ec20439d9c3ddd28bcd2b91701139f94faa11c3fc1b2b20e27552 -address /var/run/docker/containerd/containerd.sock\n17.714  runc             816772 816762   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a3341f91925ec20439d9c3ddd28bcd2b91701139f94faa11c3fc1b2b20e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a3341f91925ec20439d9c3ddd28bcd2b91701139f94faa11c3fc1b2b20e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a3341f91925ec20439d9c3ddd28bcd2b91701139f94faa11c3fc1b2b20e a3341f91925ec20439d9c3ddd28bcd2b91701139f94faa11c3fc1b2b20e27552\n17.719  exe              816781 816724   0 /proc/1599/exe -exec-root=/var/run/docker d8b5ae84470c392a0f9d6d5ca48ae45dc68f74c3ed1ae62346b75312885628ed d7da31e8f8e1\n17.720  exe              816783 816772   0 /proc/self/exe init\n17.720  rustc            816784 816738   0 /home/xmoe/.cargo/bin/rustc -vV\n17.725  rustc            816784 816738   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.734  cargo            816802 816738   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n17.740  cargo            816802 816738   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n17.740  exe              816817 1599     0 /proc/self/exe /var/run/docker/netns/a456027c1a7d all false\n17.748  rustc            816825 816802   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.749  exe              816826 816772   0 /proc/1599/exe -exec-root=/var/run/docker a3341f91925ec20439d9c3ddd28bcd2b91701139f94faa11c3fc1b2b20e27552 d7da31e8f8e1\n17.758  rustc            816841 816802   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.768  exe              816846 1599     0 /proc/self/exe /var/run/docker/netns/8497ef252f58 all false\n17.769  rustc            816847 816802   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.788  runc             816870 816714   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d8b5ae84470c392a0f9d6d5ca48ae45dc68f74c3ed1ae62346b75312885 --log-format json --systemd-cgroup start d8b5ae84470c392a0f9d6d5ca48ae45dc68f74c3ed1ae62346b75312885628ed\n17.793  sh               816737 816714   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.794  cargo            816876 816737   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.804  cargo-native-tr  816876 816737   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.807  cargo            816877 816876   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.808  runc             816878 816762   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a3341f91925ec20439d9c3ddd28bcd2b91701139f94faa11c3fc1b2b20e --log-format json --systemd-cgroup start a3341f91925ec20439d9c3ddd28bcd2b91701139f94faa11c3fc1b2b20e27552\n17.812  sh               816801 816762   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.813  cargo            816884 816801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n17.818  rustc            816885 816877   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.823  cargo-native-tr  816884 816801   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n17.826  cargo            816887 816884   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.828  rustc            816888 816877   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.836  rustc            816892 816887   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.845  rustc            816894 816887   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.888  runc             816898 813959   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db301cbf93b4da7734855703a267513f8b1c1f16612b8b7921108bf1c43 --log-format json --systemd-cgroup kill --all db301cbf93b4da7734855703a267513f8b1c1f16612b8b7921108bf1c430273c 9\n17.906  runc             816905 813959   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db301cbf93b4da7734855703a267513f8b1c1f16612b8b7921108bf1c43 --log-format json --systemd-cgroup delete db301cbf93b4da7734855703a267513f8b1c1f16612b8b7921108bf1c430273c\n18.057  containerd-shim  816911 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id db301cbf93b4da7734855703a267513f8b1c1f16612b8b7921108bf1c430273c -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db301cbf93b4da7734855703a267513f8b1c1f16612b8b7921108bf1c43 delete\n18.059  runc             816918 816911   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db301cbf93b4da7734855703a267513f8b1c1f16612b8b7921108bf1c430273 --log-format json delete --force db301cbf93b4da7734855703a267513f8b1c1f16612b8b7921108bf1c430273c\n18.096  systemd-sysctl   816923 816691   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth21a73fb --prefix=/net/ipv4/neigh/veth21a73fb --prefix=/net/ipv6/conf/veth21a73fb --prefix=/net/ipv6/neigh/veth21a73fb\n"
}
```

#### Record 28

```json
{
  "argv": [
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 814280,
  "build_script_target_dir": "tree-sitter-language-04f523abf8aa8aa2",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build",
  "pid": 814280,
  "ppid": 814221,
  "root_cargo_pid": 814221,
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
  "build_script_root_pid": 814434,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build-script-build",
  "pid": 814434,
  "ppid": 814221,
  "root_cargo_pid": 814221,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out"
}
```

#### Record 30

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-E",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/13831713749963907173detect_compiler_fami"
  ],
  "build_script_related": true,
  "build_script_root_pid": 814434,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 814435,
  "ppid": 814434,
  "root_cargo_pid": 814221,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/13831713749963907173detect_compiler_fami",
    "-msecure-plt",
    "-mcpu=power8",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 814434,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 814436,
  "ppid": 814435,
  "root_cargo_pid": 814221,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
  "build_script_root_pid": 814434,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 814437,
  "ppid": 814434,
  "root_cargo_pid": 814221,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 33

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
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o",
    "-c",
    "src/parser.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 814434,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 814438,
  "ppid": 814434,
  "root_cargo_pid": 814221,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 34

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
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 814434,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 814439,
  "ppid": 814438,
  "root_cargo_pid": 814221,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 35

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
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o",
    "/tmp/ccsrdoca.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 814434,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 814440,
  "ppid": 814438,
  "root_cargo_pid": 814221,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 36

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cqD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/libtree-sitter-java.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 814434,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 814454,
  "ppid": 814434,
  "root_cargo_pid": 814221,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 37

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "sD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/libtree-sitter-java.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 814434,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 814455,
  "ppid": 814434,
  "root_cargo_pid": 814221,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "event_id": "bsrun:ac643fa36e59a4df:5b4e52ebebf54619:416f8f7a19a7071a",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
  "success": true,
  "target": null,
  "version": "0.23.5",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  }
}
```

#### Record 40

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
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "..."
  ],
  "src": "src/parser.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 814439,
  "ppid": 814438,
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "root_cargo_pid": 814221,
  "build_script_root_pid": 814434,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 41

```json
{
  "event": "archive",
  "tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "real_tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cqD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/libtree-sitter-java.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o"
  ],
  "archive": "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/libtree-sitter-java.a",
  "objects": [
    "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 814454,
  "ppid": 814434,
  "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "root_cargo_pid": 814221,
  "build_script_root_pid": 814434,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
  "_owner": {
    "crate": "tree-sitter-java",
    "version": "0.23.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T02:44:04.092699+00:00",
  "crate": "tree-sitter-java",
  "version": "0.23.5",
  "architecture": "ppc64le",
  "duration_seconds": 30.08726561907679,
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
        "manifest_path": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5/Cargo.toml"
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
      "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "workspace_root": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5"
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
          "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
          "name": "tree-sitter-java",
          "version": "0.23.5",
          "manifest_path": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5"
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/raw-dylibs",
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
      "pid": 814248,
      "ppid": 814235,
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/raw-dylibs",
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
      "event_id": "used:cc:d9861ad91616b5cc:c1d12c051337faa0:085e3bf50b18abef",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
      "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o",
      "pid": 814248,
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/raw-dylibs",
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
      "pid": 814248,
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/raw-dylibs",
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
      "pid": 814248,
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/raw-dylibs",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/raw-dylibs",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/raw-dylibs",
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
      "context_path": "/tmp/native-trace-814143-1783997018737/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-814143-1783997018737/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 814248,
      "ppid": 814235,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/raw-dylibs",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u",
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
          "directory": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc46Il3u/symbols.o",
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
      "map_path": "/tmp/native-trace-link-cc-814248-1783997020703120745.map",
      "pid": 814248,
      "ppid": 814235,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-814248-1783997020703120745.map"
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "exit_code": 0,
      "kind": "exec",
      "pid": 814413,
      "ppid": 814396,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:23e5ba707569c0c7:a27f607962838c1e:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
      "pid": 814413,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:23e5ba707569c0c7:49d398cdf3d95d60:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
      "pid": 814413,
      "sha256": "c89f41dcce91c8e376665d637194d4ff438cde95fae307bc05c4d723c4337709",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:23e5ba707569c0c7:4d166e250a9c3d38:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
      "pid": 814413,
      "sha256": "31909db1816b6e599643976d64006df1954956bdb43f9e21ed6a000e342a7b44",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:23e5ba707569c0c7:d89591db5739b89b:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
      "pid": 814413,
      "sha256": "75fb961da3f58aeeb57ab792ef21de87322fc28e95592c368c68e94a22c126fb",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:23e5ba707569c0c7:3fe383c7b72a2c85:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
      "pid": 814413,
      "sha256": "af4875b4c44928e348197cc39309f1990ae1a60d08eb21fe4e6a819cef408d24",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:23e5ba707569c0c7:ec5e68c5d2606a22:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
      "pid": 814413,
      "sha256": "425e080599ca64030671b67fa226f456b182394b78556b99bc7b78a95fafe9f5",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:23e5ba707569c0c7:bffb1ece99f57ec6:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
      "pid": 814413,
      "sha256": "e3824b064a0622d6a9b11e8140c48f967a32c450432fe78b036c24386d0c11c6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:23e5ba707569c0c7:a3da80c9a0a91597:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
      "pid": 814413,
      "sha256": "74b13806e1f766786cf02ba3c672d591b93c02d4e96c21d29979b42f7999a32f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:23e5ba707569c0c7:b2906c80f49aa777:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
      "pid": 814413,
      "sha256": "535a8168022e7a8fa61b98bb80606470a9e505db643e9f8a5b515e550e6f4b19",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:23e5ba707569c0c7:8becfad388957269:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
      "pid": 814413,
      "sha256": "72d7a0f727472cd9e2385cc7c47cdde04d5ef9743dda0930213f2f523bc3fe3e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:23e5ba707569c0c7:26dd2a5e7828239a:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
      "pid": 814413,
      "sha256": "5d3552dcfe6396a9858071fd9dbffb5bcd3583bd5d889d6f911f50313b8a23e5",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:23e5ba707569c0c7:c5dbceecd4e81526:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
      "pid": 814413,
      "sha256": "87189e9ad602ccfa929a0c09c2d521106d7b08f6bde6616b40bbc3a646af2ebd",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "event_id": "used:cc:23e5ba707569c0c7:498d12d8fed5a13c:9d8c5a4c27d804b4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082",
      "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
      "pid": 814413,
      "sha256": "75468453c13ef230dac3751b703b1015b0a13f788d7cdd74029370ef9cdb8fcd",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "cargo_pkg_name": "tree-sitter-java",
      "cargo_pkg_version": "0.23.5",
      "context_path": "/tmp/native-trace-814143-1783997018737/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-814143-1783997018737/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 814413,
      "ppid": 814396,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b",
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
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/rustctk9H9b/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.05wdyrhz6n5sen6xmy2q3k7j4.11rbr8i.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0t5nla8dowu7d5diiysfukidb.11rbr8i.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tsa970u2h18fdc41y03j23ib.11rbr8i.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.3ozph1an6ac7iv7gm0zyqs4t6.11rbr8i.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.503e01jndkv84zdd063ad6wf2.11rbr8i.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.51e1ab3s4hv3uzfe9xzxiqt36.11rbr8i.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.7tjs2azjfs9f5hex2jd1ab55p.11rbr8i.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8evezzvp0ku6xi6l7qda0v2m8.11rbr8i.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.8ikgiyp5v8kq8g0z60ogko7df.11rbr8i.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.ef9lpgrqqfa3h65z74l8xl97e.11rbr8i.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.f2e63cvcqx18c4lpaq0idszit.11rbr8i.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build_script_build-b1b5fbae82b88082.0tglhz0ywqorjvhsez93yu5is.11rbr8i.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-814413-1783997021427401226.map",
      "pid": 814413,
      "ppid": 814396,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-814413-1783997021427401226.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
      "parsed_event_count": 451,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 452,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "1fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n13.191  collect2         815730 815728   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbw5DtH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.193  ld.lld           815736 815730   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbw5DtH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/io-lifetimes-963751d69e961f50/build_script_build-963751d69e961f50 ...\n13.194  rust-lld         815736 815730   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbw5DtH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.195  cc               815731 815607   0 /tmp/native-trace-815545-1783997031660/shims/cc -m64 /target/debug/build/io-extras-cb8206428352439e/rustcjGY8Eg/symbols.o /target/debug/build/io-extras-cb8206428352439e/build_script_build-cb8206428352439e.build_script_build.8266330570a55331-cgu.0.rcg /target/debug/build/io-extras-cb8206428352439e/build_script_build-cb8206428352439e.build_script_build.8266330570a55331-cgu.1.rcg /target/debug/build/io-extras-cb8206428352439e/build_script_build-cb8206428352439e.b2taiobdfsr84pimy1fnnf8wx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n13.198  cc               815743 815731   0 /usr/bin/cc -m64 /target/debug/build/io-extras-cb8206428352439e/rustcjGY8Eg/symbols.o /target/debug/build/io-extras-cb8206428352439e/build_script_build-cb8206428352439e.build_script_build.8266330570a55331-cgu.0.rcg /target/debug/build/io-extras-cb8206428352439e/build_script_build-cb8206428352439e.build_script_build.8266330570a55331-cgu.1.rcg /target/debug/build/io-extras-cb8206428352439e/build_script_build-cb8206428352439e.b2taiobdfsr84pimy1fnnf8wx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n13.205  collect2         815747 815743   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cca2q5PQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.207  ld.lld           815751 815747   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cca2q5PQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/io-extras-cb8206428352439e/build_script_build-cb8206428352439e ...\n13.208  rust-lld         815751 815747   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cca2q5PQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.230  cc               815793 815613   0 /tmp/native-trace-815545-1783997031660/shims/cc -m64 /target/debug/build/cap-primitives-806b2f1f5f1bc65b/rustcdgw8u5/symbols.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.0fdkdi7bwb7ms5x1w080ify2t.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.0rb6bl0t2sn5ttnmy0ll2fffi.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.0tipwih5021yrg006n0kvxn46.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.0vajyxwrtlhb21ahl339e1ann.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.1bp6sok1pqwy49ckfj76dz1ls.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.221240crkdriedvxrg1r6opf8.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.45oqd6sy3ynchq85aerdcc7ea.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.46fqj1tmaem958co8ba9j45yt.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.47khdddzqr2gxzu2bwnwyobqt.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.48b2y44akgsqgwomqhw141hnt.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.4d5ph18g5ln39b7muu1x1vnie.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.4itttmqhfcupwlihyhzhsflec.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.4yul106ehyxfh2k9vfqcrayps.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.51a2f7wb5nyfoaitzfpi2dpjw.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.55y8pfs1qmwtuq6x1nqruliw6.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.569hibj8ed1sxl75ovb9pro69.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.59d29kdnlw1k9z8b5fmcckyzr.1mi1vyz.rcgu.o ...\n13.233  cc               815795 815793   0 /usr/bin/cc -m64 /target/debug/build/cap-primitives-806b2f1f5f1bc65b/rustcdgw8u5/symbols.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.0fdkdi7bwb7ms5x1w080ify2t.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.0rb6bl0t2sn5ttnmy0ll2fffi.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.0tipwih5021yrg006n0kvxn46.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.0vajyxwrtlhb21ahl339e1ann.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.1bp6sok1pqwy49ckfj76dz1ls.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.221240crkdriedvxrg1r6opf8.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.45oqd6sy3ynchq85aerdcc7ea.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.46fqj1tmaem958co8ba9j45yt.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.47khdddzqr2gxzu2bwnwyobqt.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.48b2y44akgsqgwomqhw141hnt.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.4d5ph18g5ln39b7muu1x1vnie.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.4itttmqhfcupwlihyhzhsflec.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.4yul106ehyxfh2k9vfqcrayps.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.51a2f7wb5nyfoaitzfpi2dpjw.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.55y8pfs1qmwtuq6x1nqruliw6.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.569hibj8ed1sxl75ovb9pro69.1mi1vyz.rcgu.o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b.59d29kdnlw1k9z8b5fmcckyzr.1mi1vyz.rcgu.o ...\n13.236  collect2         815796 815795   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchif2PO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.238  ld.lld           815798 815796   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchif2PO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build_script_build-806b2f1f5f1bc65b ...\n13.241  cc               815797 815588   0 /tmp/native-trace-815554-1783997031673/shims/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustciP1E9c/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n13.241  rust-lld         815798 815796   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchif2PO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.241  cc               815799 815797   0 /usr/bin/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustciP1E9c/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n13.245  collect2         815800 815799   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHYtlm4.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.247  ld.lld           815802 815800   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHYtlm4.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db ...\n13.248  rust-lld         815802 815800   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHYtlm4.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.250  cc               815801 815602   0 /tmp/native-trace-815545-1783997031660/shims/cc -m64 /target/debug/build/rustix-8b04315b121d1c9e/rustcmfvyBM/symbols.o /target/debug/build/rustix-8b04315b121d1c9e/build_script_build-8b04315b121d1c9e.build_script_build.d69df35ee93463f2-cgu.0.rcgu.o /target/debug/build/rustix-8b04315b121d1c9e/build_script_build-8b04315b121d1c9e.build_script_build.d69df35ee93463f2-cgu.1.rcgu.o /target/debug/build/rustix-8b04315b121d1c9e/build_script_build-8b04315b121d1c9e.build_script_build.d69df35ee93463f2-cgu.2.rcgu.o /target/debug/build/rustix-8b04315b121d1c9e/build_script_build-8b04315b121d1c9e.95ev0x7gi623yv044fvtecfu2.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n13.251  cc               815803 815801   0 /usr/bin/cc -m64 /target/debug/build/rustix-8b04315b121d1c9e/rustcmfvyBM/symbols.o /target/debug/build/rustix-8b04315b121d1c9e/build_script_build-8b04315b121d1c9e.build_script_build.d69df35ee93463f2-cgu.0.rcgu.o /target/debug/build/rustix-8b04315b121d1c9e/build_script_build-8b04315b121d1c9e.build_script_build.d69df35ee93463f2-cgu.1.rcgu.o /target/debug/build/rustix-8b04315b121d1c9e/build_script_build-8b04315b121d1c9e.build_script_build.d69df35ee93463f2-cgu.2.rcgu.o /target/debug/build/rustix-8b04315b121d1c9e/build_script_build-8b04315b121d1c9e.95ev0x7gi623yv044fvtecfu2.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n13.256  collect2         815818 815803   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0Vv2no.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.257  ld.lld           815821 815818   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0Vv2no.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rustix-8b04315b121d1c9e/build_script_build-8b04315b121d1c9e ...\n13.260  rust-lld         815821 815818   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0Vv2no.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.267  cc               815838 815598   0 /tmp/native-trace-815545-1783997031660/shims/cc -m64 /target/debug/build/rustix-3ab2da0310f54ee6/rustcAwr86L/symbols.o /target/debug/build/rustix-3ab2da0310f54ee6/build_script_build-3ab2da0310f54ee6.build_script_build.ac56497bb95cd8d6-cgu.0.rcgu.o /target/debug/build/rustix-3ab2da0310f54ee6/build_script_build-3ab2da0310f54ee6.build_script_build.ac56497bb95cd8d6-cgu.1.rcgu.o /target/debug/build/rustix-3ab2da0310f54ee6/build_script_build-3ab2da0310f54ee6.build_script_build.ac56497bb95cd8d6-cgu.2.rcgu.o /target/debug/build/rustix-3ab2da0310f54ee6/build_script_build-3ab2da0310f54ee6.2iz47d1t5ckh71bpj3gcc8sdp.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n13.269  cc               815839 815838   0 /usr/bin/cc -m64 /target/debug/build/rustix-3ab2da0310f54ee6/rustcAwr86L/symbols.o /target/debug/build/rustix-3ab2da0310f54ee6/build_script_build-3ab2da0310f54ee6.build_script_build.ac56497bb95cd8d6-cgu.0.rcgu.o /target/debug/build/rustix-3ab2da0310f54ee6/build_script_build-3ab2da0310f54ee6.build_script_build.ac56497bb95cd8d6-cgu.1.rcgu.o /target/debug/build/rustix-3ab2da0310f54ee6/build_script_build-3ab2da0310f54ee6.build_script_build.ac56497bb95cd8d6-cgu.2.rcgu.o /target/debug/build/rustix-3ab2da0310f54ee6/build_script_build-3ab2da0310f54ee6.2iz47d1t5ckh71bpj3gcc8sdp.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n13.271  collect2         815840 815839   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9c3eD9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.274  ld.lld           815848 815840   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9c3eD9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rustix-3ab2da0310f54ee6/build_script_build-3ab2da0310f54ee6 ...\n13.275  rust-lld         815848 815840   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9c3eD9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.292  build-script-bu  815859 815574   0 /target/debug/build/io-lifetimes-963751d69e961f50/build-script-build\n13.294  build-script-bu  815877 815574   0 /target/debug/build/io-extras-cb8206428352439e/build-script-build\n13.296  rustc            815880 815877   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --target aarch64-unknown-linux-gnu --out-dir /target/aarch64-unknown-linux-gnu/debug/build/io-extras-c5caa310b5200703/out -\n13.297  rustc            815879 815574   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name io_lifetimes --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/io-lifetimes-2.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(wasi_ext) --cfg feature=\"default\" --check-cfg ...\n13.317  build-script-bu  815892 815575   0 /target/debug/build/libc-8a22300c8f78b6db/build-script-build\n13.317  build-script-bu  815891 815574   0 /target/debug/build/cap-primitives-806b2f1f5f1bc65b/build-script-build\n13.319  rustc            815894 815892   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n13.319  rustc            815893 815877   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --target aarch64-unknown-linux-gnu --out-dir /target/aarch64-unknown-linux-gnu/debug/build/io-extras-c5caa310b5200703/out -\n13.319  rustc            815895 815891   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --out-dir /target/aarch64-unknown-linux-gnu/debug/build/cap-primitives-0c2defdabe916bb3/out -\n13.335  build-script-bu  815907 815574   0 /target/debug/build/rustix-8b04315b121d1c9e/build-script-build\n13.338  rustc            815909 815575   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n13.338  rustc            815910 815907   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --target aarch64-unknown-linux-gnu -o - -\n13.345  rustc            815917 815891   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --out-dir /target/aarch64-unknown-linux-gnu/debug/build/cap-primitives-0c2defdabe916bb3/out -\n13.350  build-script-bu  815931 815574   0 /target/debug/build/rustix-3ab2da0310f54ee6/build-script-build\n13.350  rustc            815928 815574   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name io_extras --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/io-extras-0.18.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(can_vector) --check-cfg cfg(write_all_vectored) --cfg ...\n13.352  rustc            815932 815931   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --target aarch64-unknown-linux-gnu -o /target/aarch64-unknown-linux-gnu/debug/build/rustix-bd0120e3184d440a/out/rustix_test_can_compile -\n13.368  rustc            815944 815574   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rustix --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.44/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(alloc_c_string) --check-cfg cfg(alloc_ffi) --check-cfg ...\n13.373  rustc            815945 815891   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --out-dir /target/aarch64-unknown-linux-gnu/debug/build/cap-primitives-0c2defdabe916bb3/out -\n13.378  rustc            815948 815931   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --target aarch64-unknown-linux-gnu -o /target/aarch64-unknown-linux-gnu/debug/build/rustix-bd0120e3184d440a/out/rustix_test_can_compile -\n13.396  rustc            815958 815891   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --out-dir /target/aarch64-unknown-linux-gnu/debug/build/cap-primitives-0c2defdabe916bb3/out -\n13.400  rustc            815959 815931   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-type=rlib --emit=metadata --target aarch64-unknown-linux-gnu -o /target/aarch64-unknown-linux-gnu/debug/build/rustix-bd0120e3184d440a/out/rustix_test_can_compile -\n13.422  rustc            815970 815574   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rustix --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-1.1.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(alloc_c_string) --check-cfg cfg(alloc_ffi) --check-cfg ...\n13.951  rustc            815996 815575   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=06b7662075ecae39 ...\n13.986  cc               816010 815996   0 /tmp/native-trace-815554-1783997031673/shims/cc -m64 /target/debug/build/file-lock-e7ec189e8a3c419e/rustcuciSjo/symbols.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.3c3psple0gmv7yyyqbp3fgtcd.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.401d3kyjceojcgroawg6c9nf0.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.56ucri67nlogpucsi59dqr1hc.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.8cjtzgjhebof5tgf3ur55jtke.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.9mq8ou3x1tjs9nkpxzempsbhb.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.bm7tz27hlft2omjdgnf6azk3u.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.c7qrznfrt7tj7vr46f9y3pxbi.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.e4wu78s2munsd8k0hgjdupuy7.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.71a4npaby13yh9u2xmrbik0dn.0vbzgvk.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n13.986  cc               816011 816010   0 /usr/bin/cc -m64 /target/debug/build/file-lock-e7ec189e8a3c419e/rustcuciSjo/symbols.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.3c3psple0gmv7yyyqbp3fgtcd.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.401d3kyjceojcgroawg6c9nf0.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.56ucri67nlogpucsi59dqr1hc.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.8cjtzgjhebof5tgf3ur55jtke.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.9mq8ou3x1tjs9nkpxzempsbhb.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.bm7tz27hlft2omjdgnf6azk3u.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.c7qrznfrt7tj7vr46f9y3pxbi.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.e4wu78s2munsd8k0hgjdupuy7.0vbzgvk.rcgu.o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e.71a4npaby13yh9u2xmrbik0dn.0vbzgvk.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n13.989  collect2         816012 816011   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccP9Ez9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.990  ld.lld           816013 816012   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccP9Ez9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/file-lock-e7ec189e8a3c419e/build_script_build-e7ec189e8a3c419e ...\n13.992  rust-lld         816013 816012   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccP9Ez9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n14.049  build-script-bu  816031 815575   0 /target/debug/build/file-lock-e7ec189e8a3c419e/build-script-build\n14.051  powerpc64le-lin  816032 816031   0 /usr/bin/powerpc64le-linux-gnu-gcc -E /target/powerpc64le-unknown-linux-gnu/debug/build/file-lock-83a95664524a93ab/out/8232646621862039672detect_compiler_family.c\n14.052  cc1              816033 816032   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -imultiarch powerpc64le-linux-gnu /target/powerpc64le-unknown-linux-gnu/debug/build/file-lock-83a95664524a93ab/out/8232646621862039672detect_compiler_family.c -msecure-plt -mcpu=power8 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n14.056  powerpc64le-lin  816034 816031   0 /usr/bin/powerpc64le-linux-gnu-gcc -?\n14.059  powerpc64le-lin  816035 816031   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/file-lock-83a95664524a93ab/out/ea708c7824d36062-file_lock.o -c src/file_lock.c\n14.060  cc1              816036 816035   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu src/file_lock.c -msecure-plt -quiet -dumpbase file_lock.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/file-lock-83a95664524a93ab/out/ea708c7824d36062-file_lock.o -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections ...\n14.075  as               816037 816035   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/file-lock-83a95664524a93ab/out/ea708c7824d36062-file_lock.o /tmp/ccmBp7mY.s\n14.080  powerpc64le-lin  816038 816031   0 /usr/bin/powerpc64le-linux-gnu-ar cqD /target/powerpc64le-unknown-linux-gnu/debug/build/file-lock-83a95664524a93ab/out/libfile_lock.a /target/powerpc64le-unknown-linux-gnu/debug/build/file-lock-83a95664524a93ab/out/ea708c7824d36062-file_lock.o\n14.082  powerpc64le-lin  816039 816031   0 /usr/bin/powerpc64le-linux-gnu-ar sD /target/powerpc64le-unknown-linux-gnu/debug/build/file-lock-83a95664524a93ab/out/libfile_lock.a\n14.086  rustc            816041 815575   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name file_lock --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=9238029ecd562325 ...\n14.404  rustc            816065 815574   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fs_set_times --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fs-set-times-0.20.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=1c3bfbacd5c18ecd ...\n14.968  rustc            816084 815574   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cap_primitives --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\")) -C metadata=cc7fd8781413840f ...\n17.033  cross            816295 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n17.034  rustc            816298 816295   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.041  rustc            816298 816295   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.055  rustc            816310 816295   0 /home/xmoe/.cargo/bin/rustc -vV\n17.062  rustc            816310 816295   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.073  cargo            816320 816295   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n17.079  cargo            816320 816295   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n17.093  rustc            816329 816320   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.105  rustc            816331 816320   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.118  rustc            816335 816320   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.232  cross            816339 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n17.234  rustc            816341 816339   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.241  rustc            816341 816339   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.255  rustc            816354 816339   0 /home/xmoe/.cargo/bin/rustc -vV\n17.261  rustc            816354 816339   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.272  cargo            816364 816339   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n17.278  cargo            816364 816339   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n17.291  rustc            816373 816364   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.303  rustc            816375 816364   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.316  rustc            816379 816364   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.441  rustc            816383 816295   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.447  rustc            816383 816295   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.462  docker           816395 816295   0 /usr/bin/docker --help\n17.468  rustc            816401 816339   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.474  rustc            816401 816339   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.476  docker           816415 816295   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.489  docker           816429 816339   0 /usr/bin/docker --help\n17.489  cross            816430 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n17.490  cross            816432 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n17.490  rustc            816434 816430   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.491  rustc            816442 816432   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.491  runc             816443 1599     0 /usr/bin/runc --version\n17.495  docker-init      816465 1599     0 /usr/bin/docker-init --version\n17.496  docker           816466 816295   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.496  rustc            816434 816430   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.497  rustc            816442 816432   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.505  docker           816476 816339   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.510  rustc            816489 816432   0 /home/xmoe/.cargo/bin/rustc -vV\n17.511  rustc            816490 816430   0 /home/xmoe/.cargo/bin/rustc -vV\n17.512  runc             816491 1599     0 /usr/bin/runc --version\n17.516  docker-init      816517 1599     0 /usr/bin/docker-init --version\n17.517  rustc            816490 816430   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.518  rustc            816489 816432   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.521  runc             816525 1599     0 /usr/bin/runc --version\n17.525  docker-init      816531 1599     0 /usr/bin/docker-init --version\n17.526  docker           816534 816339   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.528  cargo            816540 816432   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n17.529  cargo            816541 816430   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n17.535  cargo            816540 816432   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n17.536  cargo            816541 816430   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n17.541  runc             816559 1599     0 /usr/bin/runc --version\n17.544  rustup           816565 816295   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.545  docker-init      816566 1599     0 /usr/bin/docker-init --version\n17.549  rustc            816575 816540   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.549  rustc            816576 816541   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.552  rustup           816577 816295   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.560  rustc            816588 816540   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.560  rustc            816589 816541   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.571  rustup           816596 816339   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.573  rustc            816597 816541   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.574  rustc            816598 816540   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.578  rustup           816607 816339   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.580  rustup           816608 816295   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.601  rustup           816632 816339   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.602  uname            816633 816295   0 /usr/bin/uname -r\n17.617  docker           816642 816295   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.624  uname            816648 816339   0 /usr/bin/uname -r\n17.640  docker           816654 816339   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.664  systemd-sysctl   816673 816671   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethbf98632 --prefix=/net/ipv4/neigh/vethbf98632 --prefix=/net/ipv6/conf/vethbf98632 --prefix=/net/ipv6/neigh/vethbf98632\n17.665  systemd-sysctl   816674 816672   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc26d400 --prefix=/net/ipv4/neigh/vethc26d400 --prefix=/net/ipv6/conf/vethc26d400 --prefix=/net/ipv6/neigh/vethc26d400\n17.677  containerd-shim  816706 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id d8b5ae84470c392a0f9d6d5ca48ae45dc68f74c3ed1ae62346b75312885628ed start\n17.680  containerd-shim  816714 816706   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id d8b5ae84470c392a0f9d6d5ca48ae45dc68f74c3ed1ae62346b75312885628ed -address /var/run/docker/containerd/containerd.sock\n17.684  runc             816724 816714   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d8b5ae84470c392a0f9d6d5ca48ae45dc68f74c3ed1ae62346b75312885 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d8b5ae84470c392a0f9d6d5ca48ae45dc68f74c3ed1ae62346b75312885 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d8b5ae84470c392a0f9d6d5ca48ae45dc68f74c3ed1ae62346b75312885 d8b5ae84470c392a0f9d6d5ca48ae45dc68f74c3ed1ae62346b75312885628ed\n17.689  exe              816731 816724   0 /proc/self/exe init\n17.690  systemd-sysctl   816735 816691   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth30a7b37 --prefix=/net/ipv4/neigh/veth30a7b37 --prefix=/net/ipv6/conf/veth30a7b37 --prefix=/net/ipv6/neigh/veth30a7b37\n17.690  systemd-sysctl   816734 816701   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe31eb68 --prefix=/net/ipv4/neigh/vethe31eb68 --prefix=/net/ipv6/conf/vethe31eb68 --prefix=/net/ipv6/neigh/vethe31eb68\n17.703  cross            816738 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n17.704  rustc            816745 816738   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.708  containerd-shim  816755 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a3341f91925ec20439d9c3ddd28bcd2b91701139f94faa11c3fc1b2b20e27552 start\n17.710  rustc            816745 816738   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.710  containerd-shim  816762 816755   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id a3341f91925ec20439d9c3ddd28bcd2b91701139f94faa11c3fc1b2b20e27552 -address /var/run/docker/containerd/containerd.sock\n17.714  runc             816772 816762   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a3341f91925ec20439d9c3ddd28bcd2b91701139f94faa11c3fc1b2b20e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a3341f91925ec20439d9c3ddd28bcd2b91701139f94faa11c3fc1b2b20e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a3341f91925ec20439d9c3ddd28bcd2b91701139f94faa11c3fc1b2b20e a3341f91925ec20439d9c3ddd28bcd2b91701139f94faa11c3fc1b2b20e27552\n17.719  exe              816781 816724   0 /proc/1599/exe -exec-root=/var/run/docker d8b5ae84470c392a0f9d6d5ca48ae45dc68f74c3ed1ae62346b75312885628ed d7da31e8f8e1\n17.720  exe              816783 816772   0 /proc/self/exe init\n17.720  rustc            816784 816738   0 /home/xmoe/.cargo/bin/rustc -vV\n17.725  rustc            816784 816738   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.734  cargo            816802 816738   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n17.740  cargo            816802 816738   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n17.740  exe              816817 1599     0 /proc/self/exe /var/run/docker/netns/a456027c1a7d all false\n17.748  rustc            816825 816802   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.749  exe              816826 816772   0 /proc/1599/exe -exec-root=/var/run/docker a3341f91925ec20439d9c3ddd28bcd2b91701139f94faa11c3fc1b2b20e27552 d7da31e8f8e1\n17.758  rustc            816841 816802   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.768  exe              816846 1599     0 /proc/self/exe /var/run/docker/netns/8497ef252f58 all false\n17.769  rustc            816847 816802   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.788  runc             816870 816714   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d8b5ae84470c392a0f9d6d5ca48ae45dc68f74c3ed1ae62346b75312885 --log-format json --systemd-cgroup start d8b5ae84470c392a0f9d6d5ca48ae45dc68f74c3ed1ae62346b75312885628ed\n17.793  sh               816737 816714   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.794  cargo            816876 816737   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.804  cargo-native-tr  816876 816737   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.807  cargo            816877 816876   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.808  runc             816878 816762   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a3341f91925ec20439d9c3ddd28bcd2b91701139f94faa11c3fc1b2b20e --log-format json --systemd-cgroup start a3341f91925ec20439d9c3ddd28bcd2b91701139f94faa11c3fc1b2b20e27552\n17.812  sh               816801 816762   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.813  cargo            816884 816801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n17.818  rustc            816885 816877   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.823  cargo-native-tr  816884 816801   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n17.826  cargo            816887 816884   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.828  rustc            816888 816877   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.836  rustc            816892 816887   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.845  rustc            816894 816887   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.888  runc             816898 813959   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db301cbf93b4da7734855703a267513f8b1c1f16612b8b7921108bf1c43 --log-format json --systemd-cgroup kill --all db301cbf93b4da7734855703a267513f8b1c1f16612b8b7921108bf1c430273c 9\n17.906  runc             816905 813959   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db301cbf93b4da7734855703a267513f8b1c1f16612b8b7921108bf1c43 --log-format json --systemd-cgroup delete db301cbf93b4da7734855703a267513f8b1c1f16612b8b7921108bf1c430273c\n18.057  containerd-shim  816911 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id db301cbf93b4da7734855703a267513f8b1c1f16612b8b7921108bf1c430273c -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db301cbf93b4da7734855703a267513f8b1c1f16612b8b7921108bf1c43 delete\n18.059  runc             816918 816911   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db301cbf93b4da7734855703a267513f8b1c1f16612b8b7921108bf1c430273 --log-format json delete --force db301cbf93b4da7734855703a267513f8b1c1f16612b8b7921108bf1c430273c\n18.096  systemd-sysctl   816923 816691   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth21a73fb --prefix=/net/ipv4/neigh/veth21a73fb --prefix=/net/ipv6/conf/veth21a73fb --prefix=/net/ipv6/neigh/veth21a73fb\n"
    },
    {
      "argv": [
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 814280,
      "build_script_target_dir": "tree-sitter-language-04f523abf8aa8aa2",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build",
      "pid": 814280,
      "ppid": 814221,
      "root_cargo_pid": 814221,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 814434,
      "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build-script-build",
      "pid": 814434,
      "ppid": 814221,
      "root_cargo_pid": 814221,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-E",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/13831713749963907173detect_compiler_fami"
      ],
      "build_script_related": true,
      "build_script_root_pid": 814434,
      "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 814435,
      "ppid": 814434,
      "root_cargo_pid": 814221,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-E",
        "-quiet",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/13831713749963907173detect_compiler_fami",
        "-msecure-plt",
        "-mcpu=power8",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 814434,
      "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 814436,
      "ppid": 814435,
      "root_cargo_pid": 814221,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 814434,
      "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 814437,
      "ppid": 814434,
      "root_cargo_pid": 814221,
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
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o",
        "-c",
        "src/parser.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 814434,
      "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 814438,
      "ppid": 814434,
      "root_cargo_pid": 814221,
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
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-Wall",
        "-Wextra",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 814434,
      "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 814439,
      "ppid": 814438,
      "root_cargo_pid": 814221,
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
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o",
        "/tmp/ccsrdoca.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 814434,
      "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 814440,
      "ppid": 814438,
      "root_cargo_pid": 814221,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "cqD",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/libtree-sitter-java.a",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/ea708c7824d36062-parser.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 814434,
      "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 814454,
      "ppid": 814434,
      "root_cargo_pid": 814221,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "sD",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-java-710e506152a22319/out/libtree-sitter-java.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 814434,
      "build_script_target_dir": "tree-sitter-java-b1b5fbae82b88082",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 814455,
      "ppid": 814434,
      "root_cargo_pid": 814221,
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
      "cwd": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "event_id": "bsrun:ac643fa36e59a4df:5b4e52ebebf54619:416f8f7a19a7071a",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
      "out_dir": "/target/debug/build/tree-sitter-java-b1b5fbae82b88082/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
      "success": true,
      "target": null,
      "version": "0.23.5",
      "_owner": {
        "crate": "tree-sitter-java",
        "version": "0.23.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5#tree-sitter-java@0.23.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-i7fiyrw0/src/tree-sitter-java-0.23.5",
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
